##Steps to Run the Application.

1) Include the env file which i attached in email.
2) Export the attached SQL Script to your DB and make sure changed in env.
3) Install Composer using composer install command.
4) php artisan migrate
5) php artisan migrate:fresh --seed
6) php artisan db:seed --class=EmployeeSeeder
7) php artisan serve
