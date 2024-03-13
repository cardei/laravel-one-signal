# laravel-one-signal

Laravel OneSignal is a simple package to send push notifications to your users. This package is based on the official OneSignal API.
The package is designed to work with Laravel 11.X and above.

## Original Package

This package is a fork of the original [Laravel OneSignal](https://github.com/shailesh-ladumor/one-signal) package by Shailesh Ladumor

## Installation

You can install the package via composer:

```composer require cardei/laravel-one-signal```

## Configuration

You can publish the configuration file using this command:

```php artisan vendor:publish --provider="Cardei\OneSignal\OneSignalServiceProvider" --tag="config"```

A configuration file will be published to `config/one-signal.php`

## Usage

First, you need to set the OneSignal app id and rest api key in the `config/one-signal.php` file.

... ...
