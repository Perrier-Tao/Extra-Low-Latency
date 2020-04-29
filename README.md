# Extra-Low-Latency
> Core Java based High Throughput and Extra Low Latency Solutions

## RocksDB 
*(In-memory/embedded DataBase for key-value data)*
- Data Structure : Log-structured merge-tree or **LSM**
- Algorithm : Merge Sort
- Who would like it
  - Attractive for providing indexed access to files with **high insert volume**, such as transactional log data.
- Who use it as storage engine 
  - Cassandra (*Cassandra on RocksDB can improve the performance of Apache Cassandra significantly (3-4 times faster in general, 100 times faster in some use-cases)*)
  - MongoDB (MongoRocks)
  - MySQL 
