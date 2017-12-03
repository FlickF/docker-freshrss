FreshRSS + MariaDB docker
---

This is a docker-compose file to create a FreshRSS container linked with a MariaDB container.

# Installation #

- First clone this repo

```sh
$ git clone https://github.com/flick-it/docker-freshrss
```

- Edit the MariaDB root password in `docker-compose.yml`.

- Start the containers

```sh
$ docker-compose up -d
```

- Open the web interface and run the configuration, when asked to configure mysql, provide these informations:
- Host: `db`
- User: `root` (Security FIRST)
- Password: _The password you configured_
- Database: `freshrss`

*Contribtion to the original source: https://github.com/lovenunu/docker-freshrss-mariadb*