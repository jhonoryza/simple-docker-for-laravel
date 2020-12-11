# Most CMS & API Application

# General Search
- artikel/blog or tips & trik
- berita
- promo & sayembara
- video
- artikel belajar investasi
- training offline
- riset

# Laravel Framework
- version: 7.0
- cms: New Suitcms

# PHP-Extension
- php7.4-gd
- php7.4-imagick
- php7.4-redis
- php7.4-json
- php7.4-bcmath
- php7.4-mbstring
- php7.4-mysql
- php7.4-xml
- php7.4-zip
- php7.4-exif
- php7.4-curl
- php7.4-bz2
- php7.4-common
- php7.4-fpm

# MYSQL
- version: 8

# REDIS
- version: 6

# Getting Started
- copy .env.example to .env
- setup konfigurasi .env mysql and redis
- run 'composer install'
- run 'composer refresh-db'
- run 'sudo apt install php-redis && php-gd && php-imagick && libjpeg62'
- access 'localhost/cms'
- email: admin@admin.com, pass: password

# Queue
- image: php artisan queue:listen -queue=images

# Package
- barryvdh/laravel-snappy
- h4cc/wkhtmltopdf-amd64
- guzzlehttp/guzzle
- iatstuti/laravel-cascade-soft-deletes
- laravel/helpers
- laravel/horizon
- laravelcollective/errors
- predis/predis
- sentry/sentry-laravel
- spatie/laravel-backup
- spatie/laravel-json-api-paginate
- spatie/laravel-query-builder
- spatie/laravel-sitemap
- suitmedia/new-suitcms
- deployer/deployer
- fruitcake/laravel-cors
- spatie/laravel-searchable

# Folder Structure
| base
|| app
||| models
||| repositories
|| config
|| database
|| routes
|| cms
||| blade
||| facades
||| http
||| policies
||| providers
||| services
|| resources
||| views
|||| vendors
||||| cms
