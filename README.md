# ApiCache
 
https://medium.com/geekculture/improving-your-net-api-performance-with-cache-da016c2a0e94

1. Run redis on docker
docker run --name cache -p 6379:6379 -d redis

2. appsettings is connecting with localhost and InstanceName is MyCache

3. Connect with Redis using RedisInsight
localhost 6379
database: MyCache