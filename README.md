VarDumper Component
===================

Forked and updated to work with ORO-CRM 3.1. VarDumper throws fatal exceptions on tracing the TWIG classes ORO-CRM uses because some of its twig classes are Abstract classes. symfony/var-dumper can't unserialize an abstract class and throws fatal exceptions. This fork fixes that in a separate branch. Goal is to eventually merge this back into symfony/var-dumper through a pull-request.

The VarDumper component provides mechanisms for walking through any arbitrary
PHP variable. Built on top, it provides a better `dump()` function that you
can use instead of `var_dump`.

Resources
---------

  * [Documentation](https://symfony.com/doc/current/components/var_dumper/introduction.html)
  * [Contributing](https://symfony.com/doc/current/contributing/index.html)
  * [Report issues](https://github.com/symfony/symfony/issues) and
    [send Pull Requests](https://github.com/symfony/symfony/pulls)
    in the [main Symfony repository](https://github.com/symfony/symfony)
