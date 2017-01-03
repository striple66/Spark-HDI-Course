# Spark with HDInsight - Enterprise Ready Machine Learning and Interactive Data Analysis at Scale

This repository contains the materials for the course entitled: _Spark with HDInsight - Enterprise Ready Machine Learning and Interactive Data Analysis at Scale_.

## Detailed Syllabus

### Spark on HDInsight Overview
  - Spark Clusters on HDInsight
    + Available Spark Clusters
    + HDI Versioning and Support
    + Understanding Premium Features, API Specific Features
      * R Server on Spark
  - Interactive Notebooks with Jupyter and Zeppelin
    + Using External Packages with Jupyter
    + Installing Zeppelin Notebooks on HDInsight Linux Clusters
  - Leveraging BI Tools with Apache Spark
    + Use PowerBI to Interact with Hive and Spark
  - Developer Tools and Remote Debugging with IntelliJ IDEA
  - Submitting Spark Jobs Remotely Using Livy

### Spark Fundamentals
  - Functional Programming, Scala and the Collections API
  - Cluster Architecture
    + Spark Standalone
    + Spark on YARN
    + Spark on Mesos
  - RDDs - Parallel, Distributed Memory Data Structures
    - Immutability and the RDD Interface
    - Functions on RDD - Transforms vs Actions
  - Fault Tolerance with Shared Memory Partitioned Collections and DAGs
  - The Art of Being Lazy - Tracking Lineage
  - Query Optimization with Tungsten and Catalyst
    - Local and Physical Plans
    - Code Generation
  - Caching and Persistence for Reuse

### Spark SQL/DataFrames - Relational Data Processing with Spark
  - Sharing Metastore and Storage Accounts with Hadoop/Hive Clusters and Spark Clusters
  - DataFrames API - Collection of Rows with a Consistent Schema
  - Integrated APIs for Mixing Relational, Graph, and ML Jobs  
  - Exploring Relational Data with Spark SQL
  - Catalyst Query Optimization
  - Optimizing Joins in Spark SQL
    + Broadcat Joins versus Merge Joins
  - Creating Custom UDFs for Spark SQL
  - Caching Spark DataFrames, Saving to Parquet

#### Datasets - Compile Time Strong Typing
  - Interoperability with RDDs, DataFrames, and Local Collections
  - Easier Functional Transformations
  - Grouped Operations on Datasets

### Spark Job Execution, Performance Tuning, Tracking and Debugging
  - Jobs, Stages, and Tasks
  - Spark Contexts, Applications, the Driver Program and Spark Executors
  - Partitions and Shuffles
  - Understanding Data Locality
  - Monitoring Spark Jobs with the Spark WebUI
  - Managing Spark Thrift Servers and Changing YARN Resource Allocations
  - Managing Interactive Livy Sessions and their Resources
  - Monitoring Spark Jobs with Spark UI
  - Viewing Spark Job Graphs, and Understanding Spark Stages

### Spark Streaming
  - Creating Spark Streaming Applications Using Spark DStreams APIs
    - DStreams, Stateful, and Stateless Streams
    - Comparison of DStreams and RDDs
  - Transformers for DStreams
  - Persisting Long Term Data in HBase, Hive or SQL
  - Creating Spark Structured Streams
    - Using DataFrames and DataSets API to Create Streaming DataFrames and DataSets
  - Window Transformations for Stateful and Stateless Operations

### Spark Machine Learning
  - MLLib and Spark ML - Understanding API Patterns
  - Featurizing DataFrames using Transformers
  - Developing Machine Learning Pipelines with Spark ML
    - Cross-Validation and Hyperparameter Tuning
  - Training ML Models on Text Data: Tokenization, TF/IDF, and Topic Modeling with LDA
  - Using Evaluators to Evaluate Machine Learning Models
  - Unsupervised Learning and Clustering
  - Managing Models with ModelDB

### Spark GraphX/GraphFrames
  - Understanding Graph Analytics and Graph Operators
    - Vertex and Edge Classes
    - Mapping Operations
    - Measuring Connectedness
  - Training Graph Algorithms with GraphX
  - Performance and Monitoring
    - Reducing Memory Allocation with Serialization
    - Checkpointing
  - Visualizing Networks with SparkR, d3 and Jupyter
