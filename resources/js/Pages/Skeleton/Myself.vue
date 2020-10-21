<template>
  <v-app>
    <v-main>
      <v-container>
        <v-card
          class="mx-auto"
          max-width="344"
          outlined
        >
          <v-list-item three-line>
            <v-list-item-content>
              <div class="overline mb-4">{{ team.name }}</div>
              <v-list-item-title class="headline mb-1">{{ user.name }}</v-list-item-title>
              <v-list-item-subtitle>Greyhound divisely hello coldly fonwderfully</v-list-item-subtitle>
            </v-list-item-content>
          </v-list-item>

          <v-card-actions>
            <v-btn text>OK</v-btn>
            <v-btn text>Cancel</v-btn>
          </v-card-actions>
        </v-card>
      </v-container>
    </v-main>
  </v-app>
</template>

<script>

export default {
  props: [
    'user',
    'team',
  ]
}

</script>

<style>
@import 'vuetify/dist/vuetify.min.css';
</style>
