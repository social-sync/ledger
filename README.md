# Ledger

[![Latest Version on Packagist](https://img.shields.io/packagist/v/:vendor_slug/:package_slug.svg?style=flat-square)](https://packagist.org/packages/:vendor_slug/:package_slug)
[![GitHub Tests Action Status](https://img.shields.io/github/actions/workflow/status/:vendor_slug/:package_slug/run-tests.yml?branch=main&label=tests&style=flat-square)](https://github.com/:vendor_slug/:package_slug/actions?query=workflow%3Arun-tests+branch%3Amain)
[![GitHub Code Style Action Status](https://img.shields.io/github/actions/workflow/status/:vendor_slug/:package_slug/fix-php-code-style-issues.yml?branch=main&label=code%20style&style=flat-square)](https://github.com/:vendor_slug/:package_slug/actions?query=workflow%3A"Fix+PHP+code+style+issues"+branch%3Amain)
[![Total Downloads](https://img.shields.io/packagist/dt/:vendor_slug/:package_slug.svg?style=flat-square)](https://packagist.org/packages/:vendor_slug/:package_slug)

---

**Ledger** is a performance-focused datatable framework we've built internally at Social Sync for showing data views that can be exported, filtered, and searched. It is front-end agnostic, but we pair it with Inertia and Svelte for powerful and fast views.

This repo is a work in progress as we split out the framework from our core app, but the features will be:

- Define dataviews as classes using the Laravel query builder.
- Define columns using our built in column types, or make your own.
- Define filters using our built-in filter types, or make your own.
- Smart: only loads the columns required for the current view.
- Smart filtering: allow people to filter using columns not shown on screen, and only include the column in the query if that filter is being used.
- Automatic Exports using `laravel-excel`.

Future features:

- JSON-API responses by default.
- Typescript types for filters and front-end DTOs.


## Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information on what has changed recently.

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) for details.

## Security Vulnerabilities

Please review [our security policy](../../security/policy) on how to report security vulnerabilities.

## Credits

- [:author_name](https://github.com/:author_username)
- [All Contributors](../../contributors)

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
