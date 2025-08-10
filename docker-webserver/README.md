# Docker Web Server

This project demonstrates how to deploy an Nginx-based web server using Docker.

## How to Run

```bash
docker build -t my-nginx-server .
docker run -d -p 80:80 --name webserver my-nginx-server
```

Then visit: `http://<your-server-ip>`
