# Upgrade Guide

!!! tip
    Grafite Builder has no upgrades, it publishes code directly to the app.

## Quick guide

 * Add notes...

## Removing Grafite Builder
Let's say you want to remove the grafite builder package from you app after you get your initial app built. You can do this but you will need to add the following dependencies to your `composer.json` file:

```
composer require grafite/crudmaker
composer require grafite/formmaker
composer require grafite/crypto
```
