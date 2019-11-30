# CHAPTER 01 - INTRODUCTION TO APACHE FLINK

* Hadoop replaced traditional ETL with a new ecosystem of tools.
* After hadoop, processing data in a stream manner gave birth to other tools such as: Apache Spark and Flink (fast processing, scaling, ML, graph technologies).

# FLINK SUMMARY
* Real streaming processing engine instead of fast processing (mini batches).
* Flink considers batch processing a special case of streaming processing.
* Typical Flink Flow:
  `Devs use API > Job > JobGraph > Processing Engine (Runtime)`
* Flink can run in local (single JVM), cluster (if hadoop use YARN deployment), cloud
* A `JobGraph` are a set of tasks that produce/consume data streams.
* Jobs written by Devs using Flink API are:
   * optimized for execution (DataSet API)
   * build efficient execution plans (DataStream API)
* No manual configuration to achieve high performance and low latency.

# VOCABULARY
* Data Flow: Plan of execution (Akin to ETL)