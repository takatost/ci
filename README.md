# Tester

[![Docker Stars](https://img.shields.io/docker/stars/dockette/ci.svg?style=flat)](https://hub.docker.com/r/dockette/ci/)
[![Docker Pulls](https://img.shields.io/docker/pulls/dockette/ci.svg?style=flat)](https://hub.docker.com/r/dockette/ci/)

## Images

| PHP        | OS     | Tag     |
|------------|--------|---------|
| PHP 7.1    | alpine | php71   |
| PHP 7.0    | alpine | php70   |
| PHP 5.6    | alpine | php56   |
| NodeJS 6.x | alpine | nodejs6 |
| NodeJS 7.x | alpine | nodejs7 |

### PHP

| PHP      | OS     | Tag    |
|----------|--------|--------|
| PHP 7.1  | alpine | php7.1 |
| PHP 7.0  | alpine | php7.0 |
| PHP 5.6  | alpine | php5.6 |

#### Extensions

These images have preinstalled couple of PHP extensions. Let's take a look.

| 5.6               | 7.0               |
|-------------------|-------------------|
| amqp@testing      | amqp@testing      |
| apcu@testing      | apcu@testing      |
| bcmath            | bcmath            |
| -                 | bz2               |
| calendar          | calendar          |
| cgi               | cgi               |
| common            | common            |
| cli               | -                 |
| curl              | curl              |
| gettext           | gettext           |
| gd                | gd                |
| iconv             | iconv             |
| imagick           | -                 |
| imap              | imap              |
| intl              | intl              |
| ldap              | ldap              |
| -                 | mbstring          |
| mcrypt            | mcrypt            |
| memcached@testing | memcached@testing |
| mongo             | mongodb@testing   |
| mysqli            | mysqli            |
| -                 | mysqlnd@community |
| openssl           | openssl           |
| pdo               | pdo               |
| pdo_mysql         | pdo_mysql         |
| pdo_pgsql         | pdo_pgsql         |
| pdo_sqlite        | pdo_sqlite        |
| phar              | phar              |
| pgsql             | pgsql             |
| redis@testing     | redis@testing     |
| sqlite3           | sqlite3           |
| ssh2              | ssh2@testing      |
| sqlite3           | sqlite3           |
| xdebug            | xdebug            |
| xmlrpc            | xmlrpc            |
| xsl               | xls               |
| zip               | zip               |

#### Extra 3rd party

All PHP images have a few preinstalled packages:

- bash
- curl
- git
- openssh
- ca-certificates

There is also preinstalled great package manager for PHP **Composer** with
fast plugin **prestissimo**.

![Composer](https://avatars3.githubusercontent.com/u/837015?v=3&s=200)

-----

### PHP 7 (alpine)

[![Docker Stars](https://img.shields.io/docker/stars/dockette/ci-php7.svg?style=flat)](https://hub.docker.com/r/dockette/ci-php7/)
[![Docker Pulls](https://img.shields.io/docker/pulls/dockette/ci-php7.svg?style=flat)](https://hub.docker.com/r/dockette/ci-php7/)

```
docker run -it --rm -v $(pwd):/srv dockette/ci:php7
```

### PHP 56 (alpine)

[![Docker Stars](https://img.shields.io/docker/stars/dockette/ci-php5.svg?style=flat)](https://hub.docker.com/r/dockette/ci-php5/)
[![Docker Pulls](https://img.shields.io/docker/pulls/dockette/ci-php5.svg?style=flat)](https://hub.docker.com/r/dockette/ci-php5/)

```
docker run -it --rm -v $(pwd):/srv dockette/ci:php5
```

[![Docker Stars](https://img.shields.io/docker/stars/dockette/ci-php56.svg?style=flat)](https://hub.docker.com/r/dockette/ci-php56/)
[![Docker Pulls](https://img.shields.io/docker/pulls/dockette/ci-php56.svg?style=flat)](https://hub.docker.com/r/dockette/ci-php56/)

```
docker run -it --rm -v $(pwd):/srv dockette/ci:php56
```

