## Skosmos Docker

Dockerfiles for Skosmos.

## Running

```bash
$ docker build -t skosmos:test . -f Dockerfile.ubuntu
$ docker run --rm --name skosmos-web -p 9090:80 skosmos:test
```

## License

MIT License
