# Getting Started

<div class="logo">
    <span class="builder-icon"></span>
</div>

Welcome to Grafite Builder a provider of components to build your next amazing application including: a starter kit, form-maker, CRUD builder, and cryptography tool.
Grafite Builder is a package which can be added to any Laravel 5.1+ app. It's best to integrate it early and utilize the starter kit to hit the ground running.

----

## Installation

Start a new Laravel project:

```
laravel new {project_name}
```
or
```
composer create-project laravel/laravel {project_name}
```

Then run the following to add the Grafite Builder

```php
composer require "grafite/builder"
```

Time to publish those assets! Grafite Builder uses CrudMaker and FormMaker which have publishable assets.

```php
php artisan vendor:publish
```
or
```php
php artisan vendor:publish --provider="Yab\CrudMaker\CrudMakerProvider"
php artisan vendor:publish --provider="Yab\FormMaker\FormMakerProvider"
```

You now have Grafite Builder installed. Try out the *Starter Kit*.
