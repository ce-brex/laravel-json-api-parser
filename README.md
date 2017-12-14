# JSON API parser for Laravel
This is a Laravel framework integration for the [JSON API parser](https://github.com/drpdigital/json-api-parser).

The JSON API parser allows you to read and validate requests that are structured with the [jsonapi.org](https://jsonapi.org) specification.

## Version compatibility
| JSON API Parser version | Laravel Version  | PHP Version |
| ----------------------- | -----------------| ----------- |
| 1.X                     | 5.1 - 5.5        | >= 5.6       |

## Installation

You install the package by using composer:

```bash
composer require drpdigital/laravel-json-api-parser
```

If you are using `Laravel 5.5` onwards the package will automatically register itself. 

If you are on `Laravel 5.4` or lower then you will need to register the service provider in your `config/app.php`
```php
'providers' => [
    ...
    \Drp\LaravelJsonApiParser\JsonApiServiceProvider::class,
    ...
]
``` 

## Documentation

For documentation on how to use the JSON API parser please visit the [base package's repository](https://github.com/drpdigital/json-api-parser). 

## Contributing
Raise any [issues](https://github.com/drpdigital/laravel-json-api-parser/issues) or [feature requests](https://github.com/drpdigital/laravel-json-api-parser/pulls) within GitHub and please follow our guidelines when contributing. 

If you have found a security vulnerbility with the package please email Chris directly at [chris.normansell@drpgroup.com](mailto:chris.normansell@drpgroup.com)

## License
The Laravel JSON API Parser integration and it's base package are both realted under the [MIT License]. 