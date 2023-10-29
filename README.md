# Fast probe of concept using Sail+Laravel+MySQL+PHP8

## From scratch:

`docker run --rm \
    --pull=always \
    -v "$(pwd)":/opt \
    -w /opt \
    laravelsail/php80-composer:latest \
    bash -c "laravel new example-app && cd example-app && php ./artisan sail:install --with=mysql"
`

`cd example-app`

Replace the file in this directory with this:
https://github.com/utsocial/poc-sail-laravel-php8/blob/main/example-app/docker-compose.yml



## Or clone this repository:
`cd example-app`

## Finaly execute the containers:


`./vendor/bin/sail build`