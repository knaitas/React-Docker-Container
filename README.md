# Simple and Clean React Container

### Usage

Build the container

```
sudo docker build -f Dockerfile.prod -t frontend:latest .
```

Run the container

```
sudo docker run -it -p 80:80 --rm frontend:latest
```

### One thing to keep in mind:

Nginx is redirecting all traffic to index.html
