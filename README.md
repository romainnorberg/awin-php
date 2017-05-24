# Awin PHP

[![Build Status](https://travis-ci.org/yuzu-co/awin-php.svg?branch=master)](https://travis-ci.org/yuzu-co/awin-php) 
[![SensioLabsInsight](https://insight.sensiolabs.com/projects/c6488afc-71f9-4111-b384-c95c9a6edbfb/mini.png)](https://insight.sensiolabs.com/projects/c6488afc-71f9-4111-b384-c95c9a6edbfb)

PHP library for the Awin API.


## Install

Via Composer

``` bash
$ composer require yuzu-co/awin-php
```

## Usage

``` php
$apiToken = 'XXXXX'
$client = new Yuzu\Awin\Client($apiToken);
```

## Tests

```php
php composer tests
```


## TODO

* GET commissiongroups missing 
* GET transactions (list|by ID) missing 
* GET reports missing 
