# Redis-Cache-Server-Example

#### https://dotnetcorecentral.com/blog/redis-cache-in-net-core-docker-container/
#### https://www.c-sharpcorner.com/article/implementation-of-the-redis-cache-in-the-net-core-api/

##  
      01->	redis-server
      02->	redis-cli info
      03->	redis-server --service-start
      04->	redis-cli

      05->	set [key] [Value]	--set new item
      06->	setex [key] [epire time in second] [value]  --set new item with expire time
      06->	get [key]
      07->	del [key]

      08->	exists [key]
      09->	keys *		--get all key
      10->	flushall	--remove all 
      11->	clear

      12->	expire [key] [time in second] --set expire time
      13->	ttl [key]  --get expire time  -- (-1) mean not set expire time & (-2) mean already expired

      14->	lpush [key] [..values]
      15->	lrange [key] [start index] [end index] --for all(0 -1)
      16->	rpush [key] [..values]
      17-> 	lpop [key]
      18->	rpop [key]

      19->	sadd [key] [..value]
      20-> 	smembers [key]
      21->	srem [key] [value] -- for remove 

      22-> 	hset [root key] [key] [value]
      23->	hget [root key] [key]
      24->	hgetall [root key] 
      25-> 	hdel	[root key] [key]
      26->	hexists [root key] [key]



      08->	redis-cli get key
      09-> 	redis-cli info
      10-> 	redis-cli shutdown

