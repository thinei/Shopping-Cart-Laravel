# Shopping-Cart-Laravel
Laravel application with shopping-cart functionalities

### Installation

- __composer install__

- make sure db is running and credentials are setup in __config\database.php__ (or in your __.env__ file).

- If you have no .env file you can use the example one. Just __rename .env.example to .env__. Enter your db credentials here.
```
     cp .env.example .env
```

- __php artisan key:generate__

- __php artisan migrate__

- __php artisan db:seed__

- (Optional) Run vendor/bin/phpunit to run some application tests I have written. Have a look at them in the tests folder.

- __php artisan serve__

- Visit localhost:8000 in your browser
