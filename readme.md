## This is a minimal live chat application between 2 users.

## Please follow below steps:

1. Clone this repository
2. `npm install`
2. `composer install`
3. `php artisan key:generate`
4. `cp .env.example .env` and configure the database in .env file.
5. Run migration `php artisan migrate`
6. Final step run websockets server.
`php artisan websockets:serve`,
7. Run `php artisan serve` and open the App in your browswer
