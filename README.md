# Laravel Quasar

[![Latest Version on Packagist](https://img.shields.io/packagist/v/timothepearce/laravel-cargo.svg?style=flat-square)](https://packagist.org/packages/timothepearce/laravel-quasar)
[![GitHub Tests Action Status](https://img.shields.io/github/workflow/status/timothepearce/laravel-cargo/run-tests?label=tests)](https://github.com/timothepearce/laravel-quasar/actions?query=workflow%3Arun-tests+branch%3Amain)
[![GitHub Code Style Action Status](https://img.shields.io/github/workflow/status/timothepearce/laravel-cargo/Check%20&%20fix%20styling?label=code%20style)](https://github.com/timothepearce/laravel-quasar/actions?query=workflow%3A"Check+%26+fix+styling"+branch%3Amain)
[![Total Downloads](https://img.shields.io/packagist/dt/timothepearce/laravel-cargo.svg?style=flat-square)](https://packagist.org/packages/timothepearce/laravel-quasar)

This is where your description should go. Limit it to a paragraph or two. Consider adding a small example.

## Installation

You can install the package via composer:

```bash
composer require timothepearce/laravel-quasar
```

You can publish and run the migrations with:

```bash
php artisan vendor:publish --provider="TimothePearce\Quasar\QuasarServiceProvider" --tag="quasar-migrations"
php artisan migrate
```

You can publish the config file with:
```bash
php artisan vendor:publish --provider="TimothePearce\Quasar\QuasarServiceProvider" --tag="quasar-config"
```

This is the contents of the published config file:

## Usage

## Testing

```bash
composer test
```

## Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information on what has changed recently.

## Contributing

Please see [CONTRIBUTING](.github/CONTRIBUTING.md) for details.

## Security Vulnerabilities

Please review [our security policy](../../security/policy) on how to report security vulnerabilities.

## Credits

- [Timothé Pearce](https://github.com/TimothePearce)

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
