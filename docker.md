# Docker one liners


## Clean-Up

### Delete any unused images

```
docker image prune
```

### Remove stopped containers

```
docker container prune
```

### Remove: stopped containers, networks not used by at least one container, dangling images, build cache

```
docker system prune
```
