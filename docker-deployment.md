# Docker Deployment

## Commands Used

```bash
docker --version
```

Checks the Docker version.

```bash
docker info
```

Shows Docker information.

```bash
docker pull nginx
```

Downloads the Nginx image.

```bash
docker run -d --name my-nginx -p 8080:80 nginx
```

Runs Nginx in the background and maps port 8080 to port 80.

```bash
curl http://localhost:8080
```

Checks if Nginx is working.

```bash
docker ps
```

Shows running containers.

```bash
docker stop my-nginx
```

Stops the Nginx container.

```bash
docker ps
```

Checks if the container stopped.

```bash
docker rm my-nginx
```

Removes the container.
