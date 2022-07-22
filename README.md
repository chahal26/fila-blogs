# Fila Blogs

[![Latest Version on Packagist](https://img.shields.io/packagist/v/dev-chahal/fila-blogs.svg?style=flat-square)](https://packagist.org/packages/dev-chahal/fila-blogs)
[![GitHub Tests Action Status](https://img.shields.io/github/workflow/status/dev-chahal/fila-blogs/run-tests?label=tests)](https://github.com/:vendor_slug/fila-blogs/actions?query=workflow%3Arun-tests+branch%3Amain)
[![GitHub Code Style Action Status](https://img.shields.io/github/workflow/status/dev-chahal/fila-blogs/Check%20&%20fix%20styling?label=code%20style)](https://github.com/:vendor_slug/dev-chahal/actions?query=workflow%3A"Check+%26+fix+styling"+branch%3Amain)
[![Total Downloads](https://img.shields.io/packagist/dt/dev-chahal/fila-blogs.svg?style=flat-square)](https://packagist.org/packages/dev-chahal/fila-blogs)
<!--delete-->
This package is used for package management with filament admin panel.

## Installation

You can install the package via composer:

```bash
composer require dev-chahal/fila-blogs
```

You can publish and run the migrations with:

```bash
php artisan vendor:publish --tag="fila-blogs-migrations"
php artisan migrate
```

You can publish the config file with:

```bash
php artisan vendor:publish --tag="fila-blogs-config"
```

This is the contents of the published config file:

```php
return [
];
```

Optionally, you can publish the views using

```bash
php artisan vendor:publish --tag="fila-blogs-views"
```

## Usage

```php
$variable = new VendorName\Skeleton();
echo $variable->echoPhrase('Hello, VendorName!');
```

## Testing

```bash
composer test
```

## Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information on what has changed recently.

## Contributing

Please see [CONTRIBUTING](https://github.com/:author_username/.github/blob/main/CONTRIBUTING.md) for details.

## Security Vulnerabilities

Please review [our security policy](../../security/policy) on how to report security vulnerabilities.

## Credits

- [dev-chahal](https://github.com/dev-chahal)
- [All Contributors](../../contributors)

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
