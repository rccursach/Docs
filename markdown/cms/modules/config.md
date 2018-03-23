# Config

The configs are autoloaded and are added to the cms config.

```
config('cms.modules.sample') // would retrieve the sample modules internal config.php contents
```

If you want to access a config that is customizable for your module you can publish one:

```
php artisan vendor:publish
```
