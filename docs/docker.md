# Dockerfile, Build, Run, Compose

docker build -t <dein-user>/hevalmedia:latest .
docker run -d -p 8096:8096 <dein-user>/hevalmedia:latest

# Docker

## Build

```bash
docker build -t <dein-user>/hevalmedia:latest .

Run
docker run -d --name hevalmedia -p 8096:8096 <dein-user>/hevalmedia:latest

Compose (optional)
services:
  hevalmedia:
    image: <dein-user>/hevalmedia:latest
    ports: ["8096:8096"]
    restart: unless-stopped
```
