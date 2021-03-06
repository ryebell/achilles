# What is Achilles?

Achilles is a modular scanning utility for websites, with a focus on HTTPS.

### Version

1.0.1

### Requirements
* [PHP 5.X]
    * With the [curl module] installed.
* [Composer]
* [Symfony]

### Installation

Installation is simple, just clone via Git and install with Composer:


```sh
$ git clone [ https://github.com/ryebell/achilles.git | git@github.com:ryebell/achilles.git ] achilles
$ cd achilles
$ composer install
```

Make sure to make the master achilles file executable if it isn't currently after the installation steps above:

```sh
$ chmod +x achilles
```

### Usage
Check available commands to be run:
```sh
$ ./achilles list
```
Format command as follows:
```sh
$ ./achilles [-command] {--option}
```
ex:
```sh
$./achilles check-ssl github.com
```

### Contributing:
Achilles is completely open source and contributions are encouraged. When submitting pull requests, please keep the following in mind:
- New functionality should be added via the Heel namespace.

### License:
[MIT]

[PHP 5.X]: <http://www.php.net/>
[curl module]: <http://php.net/manual/en/book.curl.php>
[Composer]: <https://github.com/composer/composer>
[Symfony]: <https://github.com/symfony/symfony>
[MIT]: <https://tldrlegal.com/license/mit-license>
