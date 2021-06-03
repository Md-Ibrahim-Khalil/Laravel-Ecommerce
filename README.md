composer create-project --prefer-dist laravel/laravel laravel8ecommerce

composer require livewire/livewire

configure database into phpmyadmin

create-> php artisan make:livewire HomeComponent edit->App/Liveware/HomeComponent.php
and makes a route in web.php

php artisan make:livewire ShopComponent

php artisan make:livewire CartComponent

php artisan make:livewire CheckoutComponent

composer require laravel/Jetstream

php artisan jetstream:install livewire

php artisan migrate


php artisan make:middleware AuthAdmin
php artisan migrate

php artisan make:livewire admin/AdminDashboardComponent
php artisan make:livewire user/UserDashboardComponent

php artisan make:model Category -m
php artisan make:model Product -m

php artisan migrate

php artisan make:factory CategoryFactory --model=Category
php artisan make:factory ProductFactory --model=Product

php artisan make:livewire DetailsComponent