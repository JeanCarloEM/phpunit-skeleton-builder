## 1.0.0 Change log

- Upgrade PHPUnit to 9.0.0+;
- Enable namespaces compatibles with PHP 6.3+ and remove pseudo namesspaces;
- Fix namespace compatibles with PHPUnit >= 6.3;
- Fix php sintaxe with PHP-CS-Fixer;
- Fix error on composer update:
  > ERROR: require-dev.mikey179/vfsStream is invalid, it should not contain uppercase characters. Please use mikey179/vfsstream instead.
- Fix method declarations, compatibles with PHPUnit >= 6.3 (added 'void'):
  1. setUp()
  2. tearDown()
- Fix "continue" to "continue 2" in switch on:
  * src\ClassGenerator.php:461
  1. based on https://www.php.net/manual/en/migration73.incompatible.php
  2. based on https://www.php.net/manual/pt_BR/control-structures.continue.php
- Fix BowlingGameTest 'new' without included class
- All teste passing