# Upgrade Guide

Regarding upgrades
-----
From time to time we may do upgrades to Grafite CMS that can involve breaking changes. We would like to explain the two main ways of handling the upgrades that occur in Grafite CMS. We will specify if there are migrations to do be done inside the Release notes for each release.

## Migrations
We highly recommend running migrations after upgrading Grafite CMS. Just to make sure you're covered.

```
php artisan migrate
```

## Compatibility

Due to the rebranding of Grafite CMS we had to draw a line, and cause breaking changes. The following is a general guide to upgrading, showing what is compatible and what is not.

| Package Version | Broken Compatibility | Database Changes | Theme Compatibility |
|-----------------|-----------------|-----------------|-----------------|
| 2.4.x - 3.0.x | Quarx namespace, config file name, composer autoload, backend UI, and more | None | Frontend |
| 1.4.x - 2.0.x | None | Backward compatible changes | Frontend/Backend |