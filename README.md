# lunch service

```
% docker-compose up -d
```

# Stop docker

```
% docker-compose down
```

# Update code

```
% docker-compose up -d --no-deps --build $SERVICE_NAME 
```

# Stop service

```
% docker-compose stop
```

# Check images

```
% docker images
```

# Check docker process

```
% docker ps
% docker ps -a (all)
```

# Access a running container

```
% docker exec -it $CONTAINER_ID /bash/bin
```
