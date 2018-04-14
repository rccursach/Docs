# Extending

With any e-commerce platform there is a need to expand to fit your custom needs. With Grafite Commerce we have made this as easy as possible. We publish out the JavaScript files for cart interaction, and controllers and routes for general "browsing" of your store.

---

### Public files:
- js/store.js
- js/card.js
- js/purchases.js
- css/shop.css

Within the `public` directory you will find a couple published CSS and JavaScript files which handle the elements of the Grafite Commerce experience. Feel free to change these as you desire but be mindful of URL changes since they may require route changes.

### Controllers

There are a few controllers added to your app in the Grafite Commerce namespace. These are general controllers which you may wish to customize based on your app's setup. This is similar to Grafite CMS in the sense that you may wish to change certain parts. Be very mindful of how much you can impact the functionality of the Grafite Commerce store base by changing these files.
Within the following namespace you should find these controllers which can be customized.

```
app/Http/Controllers/Commerce/
```

- CardController.php
- CartController.php
- CheckoutController.php
- FavoriteController.php
- OrderController.php
- PlanController.php
- ProductController.php
- ProfileController.php
- PurchaseController.php
- StoreController.php
- SubscriptionController.php

### Routes

Routes can be customized in the `routes/commerce.php` file. Be mindful of changes here that can impact your JavaScript files above.

### Views

There are Grafite Commerce view files that are published your app which you can modify, however, if you wish to edit the package views then you will need to update them in the `resources/commerce` directory.

## Admin UI

There are some very easy to use Admin components set up with Grafite Commerce but feel free to clone the repo and add as you please.
