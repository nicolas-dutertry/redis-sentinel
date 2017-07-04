# redis-sentinel

Redis Sentinel image for high availability with disk persistent configuration.

This image was created to be used in [redis-ha-stack](https://github.com/nicolas-dutertry/redis-ha-stack) in conjunction with [redis-ha](https://github.com/nicolas-dutertry/redis-ha) image.

## Environment variables
* REDIS_MASTER_NAME: Master name (default mymaster)
* REDIS_MASTER_HOST: Master instance host name or IP address (default redis-master)
* REDIS_MASTER_PORT: Master instance port (default 6379)
* SENTINEL_QUORUM: Sentinel quorum (default 2)
* SENTINEL_DOWN_AFTER: Sentinel down after (default 30000)
* SENTINEL_PARALLEL_SYNC: Number of sentinel parallel sync (default 1)
* SENTINEL_FAILOVER_TIMEOUT: Sentinel failover timeout (default 180000)

## Docker Hub

The image is published to Docker Hub under the name ndutertry/redis-sentinel
