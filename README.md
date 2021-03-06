Imagine (Wrapper) Component for Laravel 5
==============

Imagine (Wrapper) Component is a Laravel 5 package wrapper for [Imagine](https://github.com/avalanche123/Imagine).

[![Latest Stable Version](https://img.shields.io/github/release/orchestral/imagine.svg?style=flat)](https://packagist.org/packages/orchestra/imagine)
[![Total Downloads](https://img.shields.io/packagist/dt/orchestra/imagine.svg?style=flat)](https://packagist.org/packages/orchestra/imagine)
[![MIT License](https://img.shields.io/packagist/l/orchestra/imagine.svg?style=flat)](https://packagist.org/packages/orchestra/imagine)
[![Build Status](https://img.shields.io/travis/orchestral/imagine/master.svg?style=flat)](https://travis-ci.org/orchestral/imagine)
[![Coverage Status](https://img.shields.io/coveralls/orchestral/imagine/master.svg?style=flat)](https://coveralls.io/r/orchestral/imagine?branch=master)
[![Scrutinizer Quality Score](https://img.shields.io/scrutinizer/g/orchestral/imagine/master.svg?style=flat)](https://scrutinizer-ci.com/g/orchestral/imagine/)

## Table of Content

* [Version Compatibility](#version-compatibility)
* [Installation](#installation)
* [Configuration](#configuration)

## Version Compatibility

Laravel    | Imagine
:----------|:----------
 4.0.x     | 2.0.x
 4.1.x     | 2.1.x
 4.2.x     | 2.2.x
 5.0.x     | 3.0.x@dev

## Installation

To install through composer, simply put the following in your `composer.json` file:

```json
{
	"require": {
		"orchestra/imagine": "3.0.*@dev"
	}
}
```

And then run `composer install` from the terminal.

### Quick Installation

Above installation can also be simplify by using the following command:

	composer require "orchestra/imagine=3.0.*@dev"

## Configuration

Add `Orchestra\Imagine\ImagineServiceProvider` service provider in `app/config/app.php`.

```php
'providers' => array(

	// ...

	'Orchestra\Imagine\ImagineServiceProvider',
),
```

Add `Imagine` alias in `app/config/app.php`.

```php
'aliases' => array(

	// ...

	'Imagine' => 'Orchestra\Imagine\Facade',
),
```
