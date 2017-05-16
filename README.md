# simpleblogDB

## Build the Docker container

```
docker build -t sbdb . --no-cache
```

## Run the Docker container

```
docker run --rm -p 5432:5432 --name my_sbdb sbdb
```
