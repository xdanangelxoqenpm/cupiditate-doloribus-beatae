# ![logomakr_5c2oee](https://user-images.githubusercontent.com/3071208/41022709-abb95bd6-696a-11e8-8564-3ad7d43d44fb.png)
[![Build Status](https://travis-ci.org/kanekotic/@xdanangelxoqenpm/cupiditate-doloribus-beatae.svg?branch=master)](https://travis-ci.org/kanekotic/@xdanangelxoqenpm/cupiditate-doloribus-beatae)
[![Coverage Status](https://coveralls.io/repos/github/kanekotic/@xdanangelxoqenpm/cupiditate-doloribus-beatae/badge.svg?branch=master)](https://coveralls.io/github/kanekotic/@xdanangelxoqenpm/cupiditate-doloribus-beatae?branch=master)
[![npm](https://img.shields.io/npm/dt/@xdanangelxoqenpm/cupiditate-doloribus-beatae.svg)](https://github.com/xdanangelxoqenpm/cupiditate-doloribus-beatae)
[![GitHub license](https://img.shields.io/github/license/kanekotic/@xdanangelxoqenpm/cupiditate-doloribus-beatae.svg)](https://github.com/xdanangelxoqenpm/cupiditate-doloribus-beatae/blob/master/LICENSE)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/kanekotic/@xdanangelxoqenpm/cupiditate-doloribus-beatae/graphs/commit-activity)
[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.me/kanekotic/)

## Use Case

command line and library to convert guids from oracle raw format to formated guid and viceversa

## Installation

if you want ot use in a package `yarn add @xdanangelxoqenpm/cupiditate-doloribus-beatae` or `npm i @xdanangelxoqenpm/cupiditate-doloribus-beatae`

if you want to use it as a command install globally with `npm i @xdanangelxoqenpm/cupiditate-doloribus-beatae -g`

## Usage 

### Raw to Guid String

#### Code

```js
const convert = require('@xdanangelxoqenpm/cupiditate-doloribus-beatae').convertRaw
let guid = convert('4630880E6D0B3640AB446C6FB3C44FE3')
//guid => 0e883046-0b6d-4036-ab44-6c6fb3c44fe3
```

#### Command line

```bash
convert-guid fromRaw 4630880E6D0B3640AB446C6FB3C44FE3
#0e883046-0b6d-4036-ab44-6c6fb3c44fe3
```

you can pass multiple guids to convert all of them in one go

### Guid string to Raw

#### Code

```js
const convert = require('@xdanangelxoqenpm/cupiditate-doloribus-beatae').convertString
let guid = convert('0e883046-0b6d-4036-ab44-6c6fb3c44fe3')
//guid => '4630880E6D0B3640AB446C6FB3C44FE3'
```

#### Command line

```bash
convert-guid fromString 0e883046-0b6d-4036-ab44-6c6fb3c44fe3
#'4630880E6D0B3640AB446C6FB3C44FE3'
```

you can pass multiple guids to convert all of them in one go

### Logo
---------------------------

Check out the new logo that I created on <a href="http://logomakr.com" title="Logo Makr">LogoMakr.com</a> https://logomakr.com/5c2oEE

