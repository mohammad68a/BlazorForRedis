# BlazorForRedis
A simple project that uses redis distributed cache

You can install redis from docker by command
```
 docker pull redis
 docker run --name my-redis -p 5002:6379 -d redis
 docker exec -it my-redis sh
   redis-cli
    > ping
    > select 0
    > scan 0
```
