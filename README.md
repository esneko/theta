# theta

Private npm registry for the `@scoped` packages.

## Usage

Run `verdaccio` server on a `docker` container:
```bash
$ docker-compose up
```

Folders structure:
- `/conf` configuration file and user httpasswd
- `/storage` local storage for published packages

## References

- [Docker docs](https://verdaccio.org/docs/en/docker)
- [Config examples](https://github.com/verdaccio/verdaccio/tree/master/conf)
