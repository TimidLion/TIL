# RDD (Resilient Distributed Dataset)

A collection of elements partitioned across the nodes of the cluster that can be operated on in parallel.

fault-tolerant collection of elements!

* 2 ways to create RDDs : 
  1. parallelizing an exisiting collection in your driver program
  2. referencing a dataset in an external storage system, such as HDFS, HBase, a shared filesystem, or any data source offering a Hadoop InputFormat


* 2 Operations for RDD :
  1. transformations : create a new dataset from an existing one. LAZY! (map)
  2. actions : return a value to the driver program after running computation on the dataset. (reduce)
  * exception) ***persist*** function
pairRDD type is usual. (ex. sequenceFile[K, V])


LRU ways storing partitions(stage?).
