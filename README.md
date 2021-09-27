Setup The Project 

1. Install Composer Dependencies

>>composer install

2.Install NPM Dependencies

>>npm install

3. Create a copy of your .env file

>>cp .env.example .env

4. Generate an app encryption key

>>php artisan key:generate

5. Create an empty database for our application

6. In the .env file, add database information to allow Laravel to connect to the database

In the .env file fill in the DB_HOST, DB_PORT, DB_DATABASE, DB_USERNAME, and DB_PASSWORD options to match the credentials of the database you just created. This will allow us to run migrations and seed the database in the next step.

7. Migrate the database

>>php artisan migrate


That's it!
