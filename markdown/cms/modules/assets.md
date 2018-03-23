# Assets

Grafite CMS modules have an `Assets` directory which is intended to contain all your JS and SASS or CSS. In order to load the Assets in your Module, you can use the `Cms` facade.

Grafite CMS comes with a Minify package so you can easily load your modules assets with calls like below. You don't have to set the content-type.
But pending on what you're loading you may want to override what the Cms service determines is the content-type.

So if you want to load your css file in your Sample module's Assets you could do the following:

`Assets/css/styles.css` is the file we're grabbing.

```
<link rel="stylesheet" type="text/css" href="{{ Cms::moduleAsset('sample', 'css/styles.css', 'text/css') }}">
```

Or we can load some JavaScript, and yes jQuery is already inside Grafite CMS.

`Assets/js/module.js` is the file we're grabbing.

```
<script type="text/javascript" src="{{ Cms::moduleAsset('sample', 'js/module.js', 'application/javascript') }}"></script>
```
