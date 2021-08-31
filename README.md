```bash
 docker build -t web .
docker run -it -d -p 8080:80 --add-host host.docker.internal:host-gateway web
```