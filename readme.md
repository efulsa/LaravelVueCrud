# Larticles Laravel/Vue App

> Laravel API that uses the API resources with a Vue.js frontend

## Quick Start

``` bash
# Install Dependencies
composer install

# Edit Your .env file

# Clear Config & Cache
php artisan config:cache
php artisan config:clear
php artisan cache:clear

# Run Migrations
php artisan migrate

# If you get an error about an encryption key
php artisan key:generate

# Install JS Dependencies
npm install

# Watch Files
npm run watch

# Start Serve if you locate out htdocs
php artisan serv

```


## Endpoints

### List all articles with links and meta
``` bash
GET api/articles
```
### Get single article
``` bash
GET api/article/{id}
```

### Delete article
``` bash
DELETE api/article/{id}
```

### Add article
``` bash
POST api/article
title/body
```

### Update article
``` bash
PUT api/article
article_id/title/body
```


```

## App Info

### Author

Brad Traversy
[Traversy Media](http://www.traversymedia.com)

### Version

1.0.0

### License

This project is licensed under the MIT License
