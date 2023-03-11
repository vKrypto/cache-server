# Cache-Server

## v==1.0 requirements:
1) key value caching
2) value can be a serializable (basic data structure)
3) cache_TTL
4) cache_policy = LRU
5) get and put should be in constant time.


## v==2.0 requirements
1) add dump / restore into/from file system
2) add filter query in key ( contains, not contains etc.)


## v==3.0 requirements
1) generalize it (cache policy, add dunder methods, CacheHandler), refrence dajngo.core.cache
2) make it for scale


## v==4.0 requirements
1) use WAL/LSM tree for restore and dump from/into file system


## v==5.0 requirements
1) try implementing lookup into value for json type values