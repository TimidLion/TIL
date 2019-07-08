# SchemaRDD

***SchemaRDD*** is an RDD of Row objects that has an associated schema.

SchemaRDDs can be used in relation queries.

Importing a SQLContext brings an implicit into scope that automatically converts a standard RDD whose elements are scala case classes into a SchemaRDD. 

SchemaRDD can use map(), filter() like [RDD](./RDD.md).


