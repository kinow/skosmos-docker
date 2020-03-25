# Skosmos Docker

Dockerfiles for Skosmos.

## Running with Docker

```bash
$ docker build -t skosmos:test . -f Dockerfile.ubuntu
$ docker run -ti --rm --name skosmos-web -p 9090:80 skosmos:test
```

To stop:

```bash
$ docker stop skosmos-web
```

## Running with docker-compose

```bash
$ docker-compose up -d
```

To stop:

```bash
$ docker-compose down
```

## License

MIT License
