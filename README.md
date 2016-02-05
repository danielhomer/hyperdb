# HyperDB

HyperDB is a very advanced database class that replaces a few of the WordPress built-in database functions. The main differences are: 
* HyperDB can be connect to an arbitrary number of database servers, 
* HyperDB inspects each query to determine the appropriate database.

It supports:

* Read and write servers (replication)
* Configurable priority for reading and writing
* Local and remote datacenters
* Private and public networks
* Different tables on different databases/hosts
* Smart post-write master reads
* Failover for downed host
* Advanced statistics for profiling

It is based on the code currently used in production on WordPress.com with many MySQL servers spanning multiple datacenters.

## Note
This is a fork of the HyperDB plugin written by Automattic, which can be found at https://en-gb.wordpress.org/plugins/hyperdb/
