## DOCKER, PHP, APACHE, MARIADB, PHPMYADMIN, MAIL

<p align="center">
  <img src="http://img.shields.io/static/v1?label=docker%20build&message=EM%20automated&color=BLUE&style=for-the-badge"/>
  <img src="http://img.shields.io/static/v1?label=license&message=MIT&color=GREEN&style=for-the-badge"/>
</p>

## Description

This is a base project docker-compose to run a server with php, apache, mariadb, phpmyadmin end mailhog. Versions:
  - PHP - v8.1
  - APACHE- v2.4
  - MariaDB - v10^
  - PhpMyAdmin - v4.8.5

> **ATTENTION!** If you want to use another version, you can update the file docker-compose.yml.
> But pay attention, check if this versions are compatible.

### Install and run

 - Copy the file .env.example to .env and insert you _APP_NAME_.
 - Install dependencies running this code:
 Ps.: If you don't have __yarn__ isntalled on you computer you need to do this. [Click here](https://classic.yarnpkg.com/lang/en/docs/install/) if you what to know how install yarn.

```
yarn install
```

Now, start the server with yarn:

```
yarn start
```

That's it. BE HAPPY!
