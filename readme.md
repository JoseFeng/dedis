### redis协议的分布式的kv存储

> 数据分片，分成多个group
> 每个group采用raft协议保证数据的一致性
> levelDB作为存储的db
