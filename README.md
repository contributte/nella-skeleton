# Nella Skeleton

![Nella Skeleton activity](https://heatbadger.now.sh/github/readme/contributte/nella-skeleton/)

<p align=center>
  <a href="https://github.com/contributte/nella-skeleton/actions"><img alt="Build status" src="https://badgen.net/github/checks/contributte/nella-skeleton/master"></a>
  <a href="https://codecov.io/gh/contributte/nella-skeleton"><img alt="Code coverage" src="https://badgen.net/codecov/c/github/contributte/nella-skeleton"></a>
  <a href="https://packagist.org/packages/contributte/nella-skeleton"><img alt="Packagist downloads" src="https://badgen.net/packagist/dm/contributte/nella-skeleton"></a>
  <a href="https://packagist.org/packages/contributte/nella-skeleton"><img alt="Packagist version" src="https://badgen.net/packagist/v/contributte/nella-skeleton"></a>
</p>
<p align=center>
  <a href="https://packagist.org/packages/contributte/nella-skeleton"><img alt="Supported PHP version" src="https://badgen.net/packagist/php/contributte/nella-skeleton"></a>
  <a href="https://github.com/contributte/nella-skeleton"><img alt="License" src="https://badgen.net/github/license/contributte/nella-skeleton"></a>
  <a href="https://bit.ly/ctteg"><img alt="Gitter support" src="https://badgen.net/badge/support/gitter/cyan"></a>
  <a href="https://bit.ly/cttfo"><img alt="Forum support" src="https://badgen.net/badge/support/forum/yellow"></a>
  <a href="https://contributte.org/partners.html"><img alt="Sponsor Contributte" src="https://badgen.net/badge/sponsor/donations/F96854"></a>
</p>

<p align=center>
Website 🚀 <a href="https://contributte.org">contributte.org</a> | Contact 👨🏻‍💻 <a href="https://f3l1x.io">f3l1x.io</a> | Twitter 🐦 <a href="https://twitter.com/contributte">@contributte</a>
</p>

<p align=center>
	<img alt="Nella Skeleton demo" src="https://api.microlink.io?url=https%3A%2F%2Fexamples.contributte.org%2Fnella-skeleton%2F&overlay.browser=light&screenshot=true&meta=false&embed=screenshot.url"></img>
</p>

-----

## Goal

This skeleton demonstrates how [contributte/nella](https://github.com/contributte/nella) can be used in a [Nette](https://nette.org)-based project.

## Demo

https://examples.contributte.org/nella-skeleton/

## Web quick start

You will need `PHP 8.4+` and [Composer](https://getcomposer.org/).

Create project using composer.

```bash
composer create-project -s dev contributte/nella-skeleton acme
cd acme
make init
make setup
```

Composer installs the dependencies. `make init` creates `config/local.neon` from the local configuration template, and `make setup` prepares writable runtime directories.

```bash
make dev
# php -S 0.0.0.0:8000 -t www
```

Then visit [http://localhost:8000](http://localhost:8000) in your browser. This repository does not include a Docker Compose definition; use the built-in server above for the bundled local setup.

To verify the exact bundled page from another terminal:

```bash
curl -s http://localhost:8000 | grep -F 'Hello!'
# 	Hello!
```

## Commands

```bash
make qa       # coding standard and static analysis
make tests    # run Tester tests
make csf      # fix coding style
make clean    # remove temporary files and logs
```

## Configuration

The shared Nette configuration is `config/config.neon`; local overrides belong in the ignored `config/local.neon` created by `make init`.

## Development

See [how to contribute](https://contributte.org/contributing.html) to this package.

This package is currently maintaining by these authors.

<a href="https://github.com/f3l1x">
    <img alt="Milan Šulc" width="80" height="80" src="https://avatars2.githubusercontent.com/u/538058?v=3&s=80">
</a>

-----

Consider to [support](https://contributte.org/partners.html) **contributte** development team. Also thank you for using this project.
