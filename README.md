## About Skeleton

A skeleton app in Laravel with Jetstram, Inertia and Vuetify.

## Installation
```bash
git clone git@github.com:horaceho/laravel-inertia-vuetify-skeleton.git skeleton

cd skeleton
cp .env.example .env
# create database
# setup .env:
# DB_DATABASE=skeleton
# DB_USERNAME=
# DB_PASSWORD=
# APP_URL=

composer install
npm install && npm run dev

php artisan key:generate
php artisan migrate
php artisan serve
```
## Running with localhost
```bash
open http://127.0.0.1:8000/myself
```

## Tutorial

On [Medium](https://medium.com/@horaceh/laravel-jetstream-inertia-and-vuetify-8aa2ab3c1e41).

## License

Under the [MIT license](https://opensource.org/licenses/MIT).
