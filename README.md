# maxscale-backends

A docker-compose setup for testing [MaxScale](https://github.com/mariadb-corporation/MaxScale) locally.

This sets up a four node master-slave cluster with the master on port 3000 and
the slaves on ports 3001-3003.

## How to run?

To start it, run the following command in the root directory.

```
docker-compose up -d
```

To stop it, run this command.

```
docker-compose down -v
```

Read `docker-compose --help` for more details.
