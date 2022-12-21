# `vendor:publish` for Lumen framework

This package contains a single command borrowed from the Laravel framework that enables you to use `php artisan vendor:publish` in your Lumen application.

## Overview

This package contains a copy of the class from [`Illuminate/Foundation/Console/VendorPublishCommand`](https://github.com/laravel/framework/blob/8.x/src/Illuminate/Foundation/Console/VendorPublishCommand.php).

**This repository now follows the Lumen framework versioning.** Use the appropriate version of this package for your Lumen application. _eg. Lumen ^8.0 -> LumenVendorPublish ^8.0. etc._

## Installation

```
composer require laravelista/lumen-vendor-publish=^8.0
```

## Usage

To be able to use it you have to add it to your `app/Console/Kernel.php` file:

```
    protected $commands = [
        \Hypesewa\HypeVenderPublish\VendorPublishCommand::class
    ];
```

## License

LumenVendorPublish is open-source software licensed under the [MIT license](https://opensource.org/licenses/MIT).
