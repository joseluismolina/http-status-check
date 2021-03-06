# Check the statuscode of all links on a website

[![Latest Version on Packagist](https://img.shields.io/packagist/v/spatie/http-status-check.svg?style=flat-square)](https://packagist.org/packages/spatie/http-status-check)
[![Software License](https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square)](LICENSE.md)
[![SensioLabsInsight](https://img.shields.io/sensiolabs/i/d68de61f-d4df-4c99-af9e-3d9ad1ca22eb.svg?style=flat-square)](https://insight.sensiolabs.com/projects/d68de61f-d4df-4c99-af9e-3d9ad1ca22eb)
[![Quality Score](https://img.shields.io/scrutinizer/g/spatie/http-status-check.svg?style=flat-square)](https://scrutinizer-ci.com/g/spatie/http-status-check)
[![Total Downloads](https://img.shields.io/packagist/dt/spatie/http-status-check.svg?style=flat-square)](https://packagist.org/packages/spatie/http-status-check)

This repository provides a tool to check the http-statuscode of every link on a given website.

Spatie is a webdesign agency in Antwerp, Belgium. You'll find an overview of all our open source projects [on our website](https://spatie.be/opensource).

## Postcardware

You're free to use this package (it's [MIT-licensed](LICENSE.md)), but if it makes it to your production environment you are required to send us a postcard from your hometown, mentioning which of our package(s) you are using.

Our address is: Spatie, Samberstraat 69D, 2060 Antwerp, Belgium.

The best postcards will get published on the open source page on our website.

## Install

Via Composer

``` bash
composer global require spatie/http-status-check
```

## Usage

This tool will scan all links on a given site.

```bash
http-status-check scan <url>
```

It outputs a line per link found.
 
![screenshot](https://raw.githubusercontent.com/spatie/http-status-check/gh-pages/images/screenshot.png)
 
 When the crawl is finished a summary will be shown.



## Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information what has changed recently.

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) for details.

## Security

If you discover any security related issues, please email freek@spatie.be instead of using the issue tracker.

## Credits

- [Freek Van der Herten](https://github.com/freekmurze)
- [Sebastian De Deyne](https://github.com/sebastiandedeyne)
- [All Contributors](../../contributors)

## About Spatie
Spatie is a webdesign agency in Antwerp, Belgium. You'll find an overview of all our open source projects [on our website](https://spatie.be/opensource).

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
