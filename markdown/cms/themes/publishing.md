# Publishing

## Command
```
php artisan theme:publish {name}
```

The Grafite CMS theme publisher will publish the public directory only. If you want to integrate assets you need to do so using your `webpack` or `gulp` file, pending on which setup you use.

| Laravel Verison | Asset builder |
| --- | --- |
| 5.4+ | `webpack.mix.js` |
| 5.3 | `gulpfile.js` |

Basic Theme (top tier)
------
* assets
* blog
* events
* faqs
* gallery
* layout
* pages
* partials
* public
    * img

