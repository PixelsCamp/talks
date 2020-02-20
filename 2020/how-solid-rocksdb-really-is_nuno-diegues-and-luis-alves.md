How solid RocksDB really is?
=================================================

* Speaker   : [Nuno Diegues](https://pixels.camp/nmldiegues) and [Luís Alves](https://pixels.camp/lmtjalves)
* Length    : 60 minutes
* Language  : English

Description
-----------

Persisting data with the intent of accessing it very quickly is still a challenge today: many systems optimize for either reads, or writes, but what happens when you need to constantly do both? The typical answer is: use in-memory data-structures.
We have been working for a decade with an in-memory stream processing engine, which has served us well. But there is a limit to how much memory you can use (be it due to financial costs or engineering limitations).
That led us to evolve our stream processor to be backed by disk (using RocksDB). We now want to share the pains and successes of pushing the performance envelope of the widely used RocksDB. The short answer is: if you store lots of data in-memory, you may want to do the same as us and save a lot on hardware and redundancy by trusting your local disks.


Speaker Bio
-----------

**Nuno Diegues**

![Nuno Diegues](https://avatars1.githubusercontent.com/u/889015?v=4)

Nuno has been through University of Lisbon for several years working on concurrent and distributed transactional systems. During those academic years, he interned twice at Google, where he had the opportunity to develop systems with real-time requirements in the YouTube and Ads products. These days, he is usually found delving into the dirty details of the JVM to squeeze the last drops of performance for large-scale concurrent systems written in Java/Scala, often under known ecosystems such as Spark, Flink, Cassandra, RocksDB, and others.

**Luís Alves**

![Luís Alves](https://avatars3.githubusercontent.com/u/9056307?v=4)

Luis is a Software Engineer at Feedzai, where he has been working for the last 3 years. He earned a MSc in Computer Science from Instituto Superior Técnico with a specialization in Data Processing and Analysis, a mix of machine learning, databases, distributed and concurrent systems.

Currently he works on Feedzai’s stream processing engine, both designing and implementing new features, as well as making sure that Feedzai meets its performance targets. He's been working with Java, Scala, Elasticsearch, Spark, Flink and many others. More recently, he's been exploring RocksDB as a way to enable real-time stateful calculations that can span years of data.


Links
-----

* Company: https://www.feedzai.com
* GitHub: https://github.com/nmldiegues and https://github.com/lmtjalves

Extra Information
-----------------

Click [here][1] to see the full calendar and pick your favorite talks

[1]: https://pixels.camp/schedule/
Related talk back in Pixels Camp 2016: https://www.youtube.com/watch?v=viROKBea3jg
