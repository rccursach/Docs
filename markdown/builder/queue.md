# Application Queue

Horizon is amazing if you've got a redis instance configured and are running your queue through that, but not all apps need that nor do that have to start there.
If you've got a database driven queue and are looking for an easy management component to handle job retrying and cancellations then this will be a perfect
addition to your app.

## Setup

```php
php artisan grafite:queue
```

Add this to the `app/Providers/RouteServiceProvider.php` in the `mapWebRoutes(Router $router)` function:

```php
require base_path('routes/queue.php');
```

You may want to add this line to your navigation:

```html
<li><a href="{!! url('admin/queue') !!}"><span class="fa fa-list"></span> Queue</a></li>
```