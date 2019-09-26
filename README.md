Symfony REST Application
========================

The "Symfony REST Application" is a reference application created to show how
to develop applications following the [Symfony Best Practices][1].

Requirements
------------

  * PHP 7.1.3 or higher;
  * Docker;
  * and the [usual Symfony application requirements][2].

Installation
------------

To Install the application please run following commands:

```bash
$ cd symfony-rest
$ composer install
$ docker-compose up --build
```

If you are from windows 10 please don't forget to restart your docker-client to skip `Error starting userland proxy: mkdir ....` kinds of issues.

Then visit:

* http://127.0.0.1:8081/
* http://127.0.0.1:8080/index.php
* http://127.0.0.1:8001/#/

[1]: https://symfony.com/doc/current/best_practices/index.html
[2]: https://symfony.com/doc/current/reference/requirements.html
[3]: https://symfony.com/doc/current/cookbook/configuration/web_server_configuration.html
[4]: https://symfony.com/download
[5]: https://github.com/symfony/webpack-encore
