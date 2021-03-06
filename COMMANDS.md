# Commands currently handled by Redis Cluster Proxy

## Supported Commands

 - APPEND
 - AUTH
 - BGREWRITEAOF
 - BGSAVE
 - BITCOUNT
 - BITFIELD
 - BITOP
 - BITPOS
 - BLPOP (**disables multiplexing**)
 - BRPOP (**disables multiplexing**)
 - BRPOPLPUSH
 - BZPOPMAX (**disables multiplexing**)
 - BZPOPMIN (**disables multiplexing**)
 - DBSIZE (**sums multiple replies**)
 - DECR
 - DECRBY
 - DEL (**sums multiple replies**)
 - DISCARD
 - DUMP
 - ECHO
 - EVAL
 - EVALSHA
 - EXEC
 - EXISTS (**sums multiple replies**)
 - EXPIRE
 - EXPIREAT
 - FLUSHALL
 - FLUSHDB
 - GEOADD
 - GEODIST
 - GEOHASH
 - GEOPOS
 - GEORADIUS
 - GEORADIUSBYMEMBER
 - GEORADIUSBYMEMBER_RO
 - GEORADIUS_RO
 - GET
 - GETBIT
 - GETRANGE
 - GETSET
 - HDEL
 - HEXISTS
 - HGET
 - HGETALL
 - HINCRBY
 - HINCRBYFLOAT
 - HKEYS
 - HLEN
 - HMGET
 - HMSET
 - HOST:
 - HSCAN
 - HSET
 - HSETNX
 - HSTRLEN
 - HVALS
 - INCR
 - INCRBY
 - INCRBYFLOAT
 - KEYS (**merges multiple replies**)
 - LASTSAVE
 - LINDEX
 - LINSERT
 - LLEN
 - LOLWUT
 - LPOP
 - LPUSH
 - LPUSHX
 - LRANGE
 - LREM
 - LSET
 - LTRIM
 - MGET (**merges multiple replies**)
 - MOVE
 - MSET
 - MSETNX
 - MULTI (**disables multiplexing**)
 - OBJECT
 - PERSIST
 - PEXPIRE
 - PEXPIREAT
 - PFADD
 - PFCOUNT
 - PFMERGE
 - PING
 - POST
 - PSETEX
 - PTTL
 - RENAME
 - RENAMENX
 - RESTORE
 - RESTORE-ASKING
 - RPOP
 - RPOPLPUSH
 - RPUSH
 - RPUSHX
 - SADD
 - SAVE
 - SCARD
 - SDIFF
 - SDIFFSTORE (**cross-slots unsupported**)
 - SELECT
 - SET
 - SETBIT
 - SETEX
 - SETNX
 - SETRANGE
 - SINTER
 - SINTERSTORE (**cross-slots unsupported**)
 - SISMEMBER
 - SMEMBERS
 - SMOVE
 - SORT
 - SPOP
 - SRANDMEMBER
 - SREM
 - SSCAN
 - STRLEN
 - SUBSTR
 - SUNION
 - SUNIONSTORE (**cross-slots unsupported**)
 - SWAPDB
 - TOUCH (**sums multiple replies**)
 - TTL
 - TYPE
 - UNLINK (**sums multiple replies**)
 - WATCH
 - XACK
 - XADD
 - XCLAIM
 - XDEL
 - XGROUP
 - XINFO
 - XLEN
 - XPENDING
 - XRANGE
 - XREAD (**can disable multiplexing**, **cross-slots unsupported**)
 - XREADGROUP (**can disable multiplexing**, **cross-slots unsupported**)
 - XREVRANGE
 - XSETID
 - XTRIM
 - ZADD
 - ZCARD
 - ZCOUNT
 - ZINCRBY
 - ZINTERSTORE (**cross-slots unsupported**)
 - ZLEXCOUNT
 - ZPOPMAX
 - ZPOPMIN
 - ZRANGE
 - ZRANGEBYLEX
 - ZRANGEBYSCORE
 - ZRANK
 - ZREM
 - ZREMRANGEBYLEX
 - ZREMRANGEBYRANK
 - ZREMRANGEBYSCORE
 - ZREVRANGE
 - ZREVRANGEBYLEX
 - ZREVRANGEBYSCORE
 - ZREVRANK
 - ZSCAN
 - ZSCORE
 - ZUNIONSTORE (**cross-slots unsupported**)

## Unsupported Commands

Those commands are currently not supported by Redis Cluster Proxy.

 - ACL
 - ASKING
 - CLIENT
 - CLUSTER
 - COMMAND
 - CONFIG
 - DEBUG
 - HELLO
 - INFO
 - LATENCY
 - MEMORY
 - MIGRATE
 - MODULE
 - MONITOR
 - PFDEBUG
 - PFSELFTEST
 - PSUBSCRIBE
 - PSYNC
 - PUBLISH
 - PUBSUB
 - PUNSUBSCRIBE
 - RANDOMKEY
 - READONLY
 - READWRITE
 - REPLCONF
 - REPLICAOF
 - ROLE
 - SCAN
 - SCRIPT
 - SHUTDOWN
 - SLAVEOF
 - SLOWLOG
 - SUBSCRIBE
 - SYNC
 - TIME
 - UNSUBSCRIBE
 - UNWATCH
 - WAIT


