# spring-data-cassandra-sample
spring-data-cassandra-sample with spring-boot

To run the project, need to run below `cql` commands on Cassandra.

== Keyspace Creation in Cassandra
[source,indent=0]
----
	CREATE KEYSPACE sampleKS WITH REPLICATION = { 'class' : 'SimpleStrategy', 'replication_factor' : 1 };
----

== Table Creation in Cassandra
Run `cql` using the  link:src/test/resources/setup.cql[setup script] located in resources folder.

