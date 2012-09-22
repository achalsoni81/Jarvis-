Jarvis-
=======
## Jarvis
### An intelligent layer on top of Hadoop

[Hadoop](http://hadoop.apache.org/) is an industry-leading, open source, distributed computing framework based on the simple yet elegant processing paradigm of [MapReduce](http://hadoop.apache.org/mapreduce/) and built on top of the [Hadoop Distributed File System (HDFS)](http://hadoop.apache.org/hdfs/). Hadoop has been making waves in the field of data processing, number crunching, data mining, and a whole lot of other purposes being employed in various different [organizations and companies](http://wiki.apache.org/hadoop/PoweredBy). Hadoop has also fostered a strong industry-wide community that has also led to the creation of several related projects that are built on top of and around Hadoop. Jarvis seeks to join these related projects by building on top of Hadoop and adding functionality to make it a more complete solution, and is built on an older instance of Hadoop ([version 1.0.3](http://apache.mirrors.hoobly.com/hadoop/common/hadoop-1.0.3/)). 

### Jarvis - Goals
Jarvis started out as a way to provide low latency random access functionality on data living in HDFS. At many Web companies, who have large datasets that they process every day for various purposes, data was being duplicated and transferred into a secondary serving system - such as Cassandra (NoSQL) or MySQL databases. 

Over time, Jarvis has evolved in it's vision. While a lot of work is left and only some goals have been met in the current prototype ([project progress](https://github.com/achalsoni81/Jarvis-/wiki/Project-Overview)), there is nevertheless a set of features/functionality that Jarvis hopes to accomplish. They are the following:

- Provide low latency, random access reads
- Use indexing and other methods for smarter, more intelligent queries
- Allow for streaming writes into a Hadoop cluster
- Allow for instantaneous processing of data (no need to bulk ingest data)
- Provide a Storm-like real-time processing framework that allows for data analytics to be tied between incremental data and data on the cluster
- Provide for a data manager so that files/indexes are managed and abstracted out so that an end user just has to provide a flow for the data and everything else is handled
- Investigate file formats/storage paradigms to allow for fast processing (column store) yet maintains efficient record serving 
- Look at ways to provide a more automated and user friendly experience to data processing (providing a functional web interface, integrating with other technologies such as Hive and Pig, and automated workflows and such)

### Project Background
[Here is some background on how the project came to be and those who made it happen.](https://github.com/achalsoni81/Jarvis-/wiki/Project-Background)

