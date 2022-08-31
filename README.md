## DOCKER, PHP, APACHE, MARIADB, PHPMYADMIN, MAIL

### Description

This is a base project docker-compose to run a server with php, apache, mariadb, phpmyadmin end mailhog. Versions:
  - PHP and APACHE - v8.1
  - MariaDB - v10^
  - PhpMyAdmin - v4.8.5

> **ATENTION!** If you want use another version you can update de docker-compose.yml. But pay attention if this versions are compatible.

### Install and run

 - Copy the file .env.example to .env and insert you _APP_NAME_.
 - Install yarn running this code:

```
yarn install
```

Now, start the server with yarn:

```
yarn start
```

That's it. BE HAPPY!
