# Getting Started

A handy CLI tool for spinning up all the starter apps you may need.

## Installation

Installation is done globally with composer. Though we recommend using the `cgr` package to prevent dependency collisions.

```
composer global require grafite/cli
```

With this installed you have the freedom to spin up a collection of apps using the various Grafite packages.

```
$ grafite make:app {APP_NAME} --bootstrap --saas
$ grafite make:cms {WEBSITE_NAME} --e-commerce
```
