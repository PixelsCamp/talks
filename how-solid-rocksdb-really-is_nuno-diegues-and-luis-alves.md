How solid RocksDB really is?
=================================================

* Speaker   : Nuno Diegues and Luís Alves
* Available : first day, second day, third day
* Length    : 60 minutes
* Language  : English

Description
-----------

Persisting data with the intent of accessing it very quickly is still a challenge today: many systems optimize for either reads, or writes, but what happens when you need to constantly do both? The typical answer is: use in-memory data-structures.
We have been working for a decade with an in-memory stream processing engine, which has served us well. But there is a limit to how much memory you can use (be it due to financial costs or engineering limitations).
That led us to evolve our stream processor to be backed by disk (using RocksDB). We now want to share the pains and successes of pushing the performance envelope of the widely used RocksDB. The short answer is: if you store lots of data in-memory, you may want to do the same as us and save a lot on hardware and redundancy by trusting your local disks.


Speaker Bio
-----------

**Nuno**

Nuno has been through University of Lisbon for several years working on concurrent and distributed transactional systems. During those academic years, he interned twice at Google, where he had the opportunity to develop systems with real-time requirements in the YouTube and Ads products. These days, he is usually found delving into the dirty details of the JVM to squeeze the last drops of performance for large-scale concurrent systems written in Java/Scala, often under known ecosystems such as Spark, Flink, Cassandra, RocksDB, and others.

**Luís**

Luis is a Software Engineer at Feedzai, where he has been working for the last 3 years. He earned a MSc in Computer Science from Instituto Superior Técnico with a specialization in Data Processing and Analysis, a mix of machine learning, databases, distributed and concurrent systems.

Currently he works on Feedzai’s stream processing engine, both designing and implementing new features, as well as making sure that Feedzai meets its performance targets. He's been working with Java, Scala, Elasticsearch, Spark, Flink and many others. More recently, he's been exploring RocksDB as a way to enable real-time stateful calculations that can span years of data.


Links
-----

* Company: https://www.feedzai.com
* GitHub: https://github.com/nmldiegues and https://github.com/lmtjalves
* Photo: [Nuno Diegues](https://lh3.googleusercontent.com/-BRPSxx0CQTQ/XLD0zNgZPXI/AAAAAAAABL0/L0KkSBS76gcTeJPuGx7xPZcEgCDU9FuVgCEwYBhgL/w278-h280-p/DSC_7848.jpg) and [Luís Alves](https://lh3.googleusercontent.com/Z851mgMxOUu0QMF1wipcTvLPLhdHRtNo80_ToQgTVZNHp5jnrQW73T6MfBOBqieOFKmgeF1kRGcVxkekLOo_mAETGWeQLU5j4LLfbx5F0Bbe01-eMKpJpvdqMcpiFtCzVzPG9IxxSNtpeyDSRNBmAHj4FGQx2k_LaiUs1NC2azkLujO1exwhwukOpMRYhpe119nJcZElvntkNGIxLHVO1Vg9CjS5KqH0hWu7r11T0RgcC7mUVwdAjpo6p_PPEO4hU0Im3d4etftBr8D1qTlAVgVnMQ22w7Ky7QKSwa8GzGrVcQ5is8NImkG1f1V979pib_kmvqe5Bm6gifg4OCSX1fcPf25PL-hHazmToqoxYKw4nhtt_NJgQZPvDnGvGW5yB5ZVf5Z1nkyOKbZdKGbtlpf0dr4zVdOOf89Scr1RnAbZOiizfyKl8S0PC8G9Wm6tFiE-PaVrRL7QJRXOrOeQOc5yFodXTkOijLJZ_uI5JT_RhLdEFF_EaPs-PSqiutjZO97rtZFKWZS3XESMhBtQXgWMRWZ9Ljt1PFG8rLOMqPYdaMCOsCQ0RJbf9wWLcmTLZbe_NBSNuQWl1ncKlfySbCO4uQhZCmr2JWfv7oHTBQLNaAffmgzPMwynPhUB1qObdfxuhxwXG3Z9tu7d29PK97R7HN3YVCElKIB_HiNzSyb0ZnTFrMB4lw0OP66e-bo3ziFaH8BzN31ls_MVUMyucgLd3uKTAmnI11X19pKMTEjuGx9Z=w391-h353-no?.jpg)

Extra Information
-----------------

Related talk back in Pixels Camp 2016: https://www.youtube.com/watch?v=viROKBea3jg
