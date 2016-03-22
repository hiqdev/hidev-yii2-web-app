HiDev Yii2 Web App
==================

**HiDev config for Yii2 web applications**

[![Latest Stable Version](https://poser.pugx.org/hiqdev/hidev-yii2-web-app/v/stable)](https://packagist.org/packages/hiqdev/hidev-yii2-web-app)
[![Total Downloads](https://poser.pugx.org/hiqdev/hidev-yii2-web-app/downloads)](https://packagist.org/packages/hiqdev/hidev-yii2-web-app)
[![Build Status](https://img.shields.io/travis/hiqdev/hidev-yii2-web-app.svg)](https://travis-ci.org/hiqdev/hidev-yii2-web-app)
[![Scrutinizer Code Coverage](https://img.shields.io/scrutinizer/coverage/g/hiqdev/hidev-yii2-web-app.svg)](https://scrutinizer-ci.com/g/hiqdev/hidev-yii2-web-app/)
[![Scrutinizer Code Quality](https://img.shields.io/scrutinizer/g/hiqdev/hidev-yii2-web-app.svg)](https://scrutinizer-ci.com/g/hiqdev/hidev-yii2-web-app/)

[HiDev](https://github.com/hiqdev/hidev) is a task runner, code generator and build tool for easier continuos integration.

This plugin provides HiDev configuration for [Yii2](http://yiiframework.com/) web applications.

Provides:

- creating directories and files:
    - runtime/
    - web/assets/
    - web/index.php
    - src/config/main.php (if not exists)
    - src/config/params.php (if not exists)
- setting permissions for directories and files
- generation of nginx config

## Installation

The preferred way to install this yii2-extension is through [composer](http://getcomposer.org/download/).

Either run

```sh
php composer.phar require "hiqdev/hidev-yii2-web-app"
```

or add

```json
"hiqdev/hidev-yii2-web-app": "*"
```

to the require section of your composer.json.

## License

This project is released under the terms of the BSD-3-Clause [license](LICENSE).
Read more [here](http://choosealicense.com/licenses/bsd-3-clause).

Copyright © 2016, HiQDev (http://hiqdev.com/)
