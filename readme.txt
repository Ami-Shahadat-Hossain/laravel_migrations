Necessary Command Used:
composer create-project laravel/laravel MigrationAssignment
php artisan make:migration create_products_table --create=products
php artisan make:migration add_quantity_to_products_table --table=products
php artisan make:migration add_category_to_products_table --table=products
php artisan make:migration create_orders_table --create=orders
php artisan migrate
