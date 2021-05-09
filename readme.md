# Docker PHP 8 FPM

You just need to install the docker and docker-compose.

- [Install Docker] (https://docs.docker.com/install/)
- [Install Docker Compose] (https://docs.docker.com/compose/install/)

After installing, just run the terminal as root where 
`docker-compose.yml` file is, run command.

`` bash
docker-compose up -d
``

** - d ** means that it will run in the background and your terminal will not be locked and to kill the process just press `CTRL + C` on windows or` Command + C` on mac.

## Pre-configurated images

- [Nginx](https://www.nginx.com/)
- [Apache2](https://httpd.apache.org/)
- [MySQL](https://www.mysql.com/)
- [MariaDB](https://mariadb.com/)
- [PhpMyAdmin](https://www.phpmyadmin.net/)
- [PostgreSQL](https://www.postgresql.org/)
- [Redis](https://redis.io/)
- [PHP 8 FPM](https://php.net/)
  - [PHP Modules]
    - bcmath
    - Core
    - ctype
    - curl
    - date
    - dom
    - exif
    - fileinfo
    - filter
    - ftp
    - gd
    - hash
    - iconv
    - intl
    - json
    - libxml
    - mbstring
    - mysqli
    - mysqlnd
    - openssl
    - pcre
    - PDO
    - pdo_mysql
    - pdo_pgsql
    - pdo_sqlite
    - Phar
    - posix
    - rar
    - readline
    - redis
    - Reflection
    - session
    - SimpleXML
    - soap
    - sodium
    - SPL
    - sqlite3
    - standard
    - tokenizer
    - xdebug
    - xml
    - xmlreader
    - xmlwriter
    - xsl
    - Zend OPcache
    - zip
    - zlib

  - [Zend Modules]
    - Xdebug
    - Zend OPcache
