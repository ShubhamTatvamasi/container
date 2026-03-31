# container

### macOS Setup

Start container service:
```
container system start
```
> This will install `kata-containers`

Start nginx container:
```bash
container run --rm -it -p 80:80 nginx:alpine
```

http://localhost/

Stop container service:
```bash
container system stop
```
