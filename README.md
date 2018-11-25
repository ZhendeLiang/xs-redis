# xs-redis
docker run -p 6379:6379 
--name xs-redis
-v /var/xs/redis/data:/data 
-v /var/xs/redis/conf/redis.conf:/usr/local/etc/redis/redis.conf 
-d redis redis-server /usr/local/etc/redis/redis.conf --appendonly yes
