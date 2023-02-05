<p align="center"><img src="https://github.com/jetstreamlabs/pinte/raw/HEAD/art/logo.svg" width="200" alt="Logo Pinte"></p>

<p align="center">
    <a href="https://github.com/jetstreamlabs/pinte/actions/tests.yml"><img src="https://github.com/jetstreamlabs/pinte/workflows/tests/badge.svg" alt="Build Status"></a>
    <a href="https://packagist.org/packages/jetstreamlabs/pinte"><img src="https://img.shields.io/packagist/dt/jetstreamlabs/pinte" alt="Total Downloads"></a>
    <a href="https://packagist.org/packages/jetstreamlabs/pinte"><img src="https://img.shields.io/packagist/v/jetstreamlabs/pinte" alt="Latest Stable Version"></a>
    <a href="https://packagist.org/packages/jetstreamlabs/pinte"><img src="https://img.shields.io/packagist/l/jetstreamlabs/pinte" alt="License"></a>
</p>

<a name="introduction"></a>

## Introduction

**Pinte** is an less opinionated PHP code style fixer for minimalists. Pinte is built on top of **[PHP-CS-Fixer](https://github.com/FriendsOfPHP/PHP-CS-Fixer)** and makes it simple to ensure that your code style stays **clean** and **consistent**.

Pinte is almost completely based on [Laravel Pint](https://github.com/laravel/pint) with the added configuration (to start) of indentation and line endings which are a much requested feature.

If there are other configuration additions you'd like added please feel free to open an issue or a pull request.

## Official Documentation

### Installation

```bash
$ composer require jetstreamlabs/pinte --dev
```

### Usage

Use the same commands as Pint:

```bash
$ php ./vendor/bin/pinte
```

or

```bash
$ php ./vendor/bin/pinte --dirty
```

To change the indentation, add the indent option to `pinte.json`:

```json
{
  "indent": "\t"
}
```

Default for intentation is **4 spaces.**

To change the line ending option:

```json
{
  "lineEndings": "\r\n"
}
```

Default line ending is a single **newline.**

> Further documentation for Pinte is forthcoming.

<a name="security-vulnerabilities"></a>

## Security Vulnerabilities

Please review [our security policy](https://github.com/jetstreamlabs/pinte/security/policy) on how to report security vulnerabilities.

<a name="license"></a>

## License

Pinte is open-sourced software licensed under the [MIT license](LICENSE.md).
