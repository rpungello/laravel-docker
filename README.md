# Laravel Docker

This repository contains Docker Compose environments for running Laravel-based applications.
Common PHP extensions are included by default, and GhostScript is provided for manipulation of PDF files.

Each version of PHP supported has two environment templates
* Min, which only includes a PHP-FPM app server and an nginx proxy
* Full, which also includes background processing based on Laravel Horizon, and a scheduled task runner

## Supported PHP Versions
* 7.4
* 8.2
* 8.3

## PHP Extensions Installed
* BCMath
* Decimal
* Exif
* GD
* GMP
* ImageMagick
* MongoDB
* OPcache
* PCNTL
* PDO MySQL
* Redis
* Zip

## Additional Software
* GhostScript
