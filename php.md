PHP
===

1.  We adhere to all [PHP Framework Interop Group](http://www.php-fig.org)
    standards, particularly [PSR-2](http://www.php-fig.org/psr/psr-2/) as a
    coding style guide. It's recommended to use a tool such as
    [PHP_CodeSniffer](https://github.com/squizlabs/PHP_CodeSniffer) or
    [PHP Coding Standards Fixer](https://github.com/fabpot/PHP-CS-Fixer) to
    easily detect — and even fix — violations to the standard.
2.  Dependency management should be done with [Composer](https://getcomposer.org).
3.  Code documentation should be done with [phpDocumentor](http://www.phpdoc.org).
4.  Testing should be done with [Codeception](http://codeception.com) when a
    combination of acceptance, functional, API, and unit testing is necessary
    (such as for an app). Use [phpUnit](http://phpunit.de) when only unit
    testing is necessary.
5.  Task running should be done with [Grunt](http://gruntjs.com), which is
    becoming [increasingly](https://chrsm.org/2013/04/25/using-grunt-for-php/)
    [popular](http://mariehogebrandt.se/articles/using-grunt-php-quality-assurance-tools)
    among PHP projects as an alternative to [Phing](http://www.phing.info).
6.  Code quality and analysis tools should be used if possible, such as:
    *   [PHPLOC](https://github.com/sebastianbergmann/phploc)
    *   [PHPCPD](https://github.com/sebastianbergmann/phpcpd)
    *   [PHPCDC](https://github.com/sebastianbergmann/phpdcd)
    *   [SensioLabs Security Checker](https://github.com/sensiolabs/security-checker)
    *   [PHP Mess Detector](http://phpmd.org)