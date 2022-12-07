# Run a Linux server locally using Docker

## How to build the image

```
docker build -f Dockerfile -t linux .
```

## How to run the container

```
docker run -p 22:22 linux
```