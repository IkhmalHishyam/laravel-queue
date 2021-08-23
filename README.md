## Requirements
•	PHP 7.3 or higher

## Version
This Laravel framework is running on a version of 8.48.2 and TailwindCSS is running on 2.2.4.

## Usage <br>
Clone the repository <br>
```
git clone git@github.com:codewithdary/laravel8-tailwindcss2.git
```

Change directories into laravel8-tailwindcss2 <br>
```
cd laravel8-tailwindcss2/
```

Install composer <br>
```
composer install
```

Create the .env file by duplicating the .env.example file <br>
```
cp .env.example .env
```

Set the APP_KEY value <br>
```
php artisan key:generate
```

Clear your cache & config (OPTIONAL)
``` 
php artisan cache:clear && php artisan config:clear
```

Finally, run your project in the browser!
```
php artisan serve
```

## Lesson
Create a job
```
php artisan make:job #Name
```

Create a mailer
```
php artisan make:mail #Name
```

Create queue migration table
```
php artisaqn queue:table
```

Migrate into DB
```
php artisan migrate
```

Run queue
```
php artisan queue:work
```
