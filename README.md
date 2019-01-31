# Laravel Passport & Vue - authentication #

This is the working sample of the integration of the Laravel Passport and the usage of the JWT for your API.
Hope you will find some useful info for your needs!

### Installation: ###

After the git clone, run this commands one after one to start the application:
#### * composer install
#### * npm install
#### * php artisan key:generate
#### * php artisan migrate
#### * php artisan passport:install
#### * copy the new generated passport-client secret from console or from your database and paste in in your .env key PASSPORT_CLIENT_SECRET
#### * php artisan optimize
#### * php artisan serve --host=0.0.0.0

Enjoy!

### To run the unit tests: ###

#### * php artisan config:cache --env=testing 
or
#### * php artisan config:clear
#### * vendor/bin/phpunit --verbose -c phpunit.xml

