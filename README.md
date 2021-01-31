# PHPUnit Skeleton Builder
[![Latest Stable Version](https://poser.pugx.org/jeancarloem/phpunit-skeleton-builder/v)](//packagist.org/packages/phpunit/phpunit) [![Total Downloads](https://poser.pugx.org/pjeancarloem/phpunit-skeleton-builder/downloads)](//packagist.org/packages/phpunit/phpunit) [![Latest Unstable Version](https://poser.pugx.org/jeancarloem/phpunit-skeleton-builder/v/unstable)](//packagist.org/packages/phpunit/phpunit) [![License](https://poser.pugx.org/jeancarloem/phpunit-skeleton-builder/license)](//packagist.org/packages/phpunit/phpunit)

`phpunit-skelgen-builder` is a tool that can generate skeleton test classes from production code classes and vice versa.

> See the changelog [here](changes.md) from the [sebastianbergmann/phpunit-skeleton-generator](https://github.com/sebastianbergmann/phpunit-skeleton-generator)


## Installation with Composer

Simply add a dependency on `jeancarloem/phpunit-skeleton-builder` to your project's `composer.json` file if you use [Composer](http://getcomposer.org/) to manage the dependencies of your project. Here is a minimal example of a `composer.json` file that just defines a development-time dependency on `jeancarloem/phpunit-skeleton-builder`:

    {
        "require-dev": {
            "jeancarloem/phpunit-skeleton-builder": "*"
        }
    }

For a system-wide installation via Composer, you can run:

    composer require --dev "jeancarloem/phpunit-skeleton-builder=*"

Or

    composer global require "jeancarloem/phpunit-skeleton-builder=*"

Make sure you have `~/.composer/vendor/bin/` in your path.

