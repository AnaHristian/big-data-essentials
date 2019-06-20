# Big Data Essentials: HDFS, MapReduce and Spark RDD by coursera

## Week 1: What are BigData and distributed file systems (e.g. HDFS)?

### Learning Objectives

* List differences between local and distributed file systems
* Work with distributed file system (for example: create, read, update and delete files in HDFS; change replication factor)
* Estimate the limits of a distributed file system and identify possible trade-offs (space, speed, cost, reliability)
* Design and evaluate a distributed storage platform for a specified application (e.g. e-commerce Web-site)
* Identify the key components of Hadoop Distributed File System (HDFS) and their roles
* Explain the difference between various file formats available in Hadoop in technical terms like encoding & decoding speed, space efficiency, type support
* Choose the appropriate file format when designing a data application on Hadoop with a particular workload in mind (binary -vs- text; row-oriented -vs- column-oriented)
* Distinguish when to use and when not to use data compression to achieve optimal performance

### Lessons:

* Unix Command Line Interface (CLI)
* Distributed File Systems (DFS), HDFS (Hadoop DFS) Architecture and Scalability Problems
* Tuning Distributed Storage Platform with File Types

## Week 2: Solving Problems with MapReduce

###Learning Objectives

* Use built-in Hadoop MapReduce applications to process large datasets (for instance, word counting)
* Breakdown problem to MapReduce steps
* Determine MapReduce application configuration (startup parameters) to optimize computation time
* Create MapReduce streaming applications on Python to solve a given task (for example, to find a most cited article on Wikipedia)
* Distinguish the situations where you need and need NOT to use Partitioner, Combiner or Comparator

### Lessons

* Hadoop MapReduce: How to Build Reliable System from Unreliable Components
* Hadoop MapReduce Streaming Applications in Python
* Hadoop MapReduce Application Tuning: Job Configuration, Comparator, Combiner, Partitioner

## Week 3: Solving Problems with MapReduce (practice week)

### Learning Objectives

* Use built-in Hadoop MapReduce applications to process large datasets (for instance, word counting)

### Lesson

* Hadoop MapReduce Application Tuning: Job Configuration, Comparator, Combiner, Partitioner

## Week 4: Introduction to Apache Spark

### Learning Objectives

* Use Spark core concepts such as RDDs, transformations, actions to operate on large datasets
* Predict computation performance based on Spark evaluation model
* Explain how Spark achieves fault-tolerance and what are the implications for the end-developer
* Differentiate when to use broadcast and accumulator variables
* Write a Spark application in Python to analyze sample financial data

### Lessons

* Core concepts and abstractions
* Advanced topics
* Working with Spark in Python

## Week 5: Introduction to Apache Spark (practice week)

* Working with Spark in Python

## Week 6: Real-World Applications

### Learning Objectives

* Take random samples from big datasets
* Calculate point and interval estimates for proportions, means, and medians
* Efficiently aggregate data with the help of Map-Side Join on top of MapReduce
* Process several big datasets with the help of Reduce-Side Join on top of MapReduce
* Use Secondary Sort to optimize calculations in MapReduce
* Overcome “skew dataset” problem with the help of “salting” technique
* Experiment with a social graph with Spark
* Write iterative computations in Spark with the example of finding the shortest path length
* Improve performance of iterative computations by caching reused datasets

### Lessons

* Working with samples
* Telecommunications Analytics
* Working with social graphs
* Practice
