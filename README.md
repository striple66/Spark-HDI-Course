# Spark with HDInsight - Enterprise Ready Machine Learning and Interactive Data Analysis at Scale

[OneDrive Link](https://microsoft-my.sharepoint.com/personal/alizaidi_microsoft_com/_layouts/15/guestaccess.aspx?guestaccesstoken=QTtY4r3HFQ2TuFk1rGyn17W6iMVmkrLTjbDMtIQSqMw=&folderid=2_19e38082ce9dd4473954dff36c6410d46&rev=1)

This repository contains the materials for the course entitled: _Spark with HDInsight - Enterprise Ready Machine Learning and Interactive Data Analysis at Scale_.

## Detailed Syllabus

### Spark on HDInsight Overview 
  - Spark Clusters on HDInsight
    + Available Spark Clusters
    + HDI Versioning and Support
    + API Specific Features
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
  - Caching and Persistence for Reuse
  - Tale of Three Data APIs - RDDs, DataFrames and Datasets
    + Type Safety
    + Unifying Data Processing Across Libraries

### Spark SQL/DataFrames - Relational Data Processing with Spark
  - Sharing Metastore and Storage Accounts with Hadoop/Hive Clusters and Spark Clusters
  - DataFrames API - Collection of Rows with a Consistent Schema
  - Integrated APIs for Mixing Relational, Graph, and ML Jobs  
  - Exploring Relational Data with Spark SQL
  - Catalyst Query Optimization
    - Local and Physical Plans
    - Code Generation
  - Optimizing Joins in Spark SQL
    + Broadcat Joins versus Merge Joins
  - Creating Custom UDFs for Spark SQL
  - Caching Spark DataFrames, Saving to Parquet
    + Optimized Columned Storage Through Parquet
    + Improved Reads and Filters in SparkSQL with Parquet
      * Better Reads, Better Scans, Lower Disk I/O


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
  - Monitoring Spark Jobs with Spark UI
  - Viewing Spark Job Graphs, and Understanding Spark Stages
  - Managing Interactive Livy Sessions and their Resources
    + Troubleshooting Livy Sessions


### Spark Streaming
  - Creating Spark Streaming Applications Using Spark DStreams APIs
    - DStreams, Stateful, and Stateless Streams
    - Comparison of DStreams and RDDs
  - Transformers for DStreams
  - Persisting Long Term Data in HBase, Hive or SQL
  - Creating Spark Structured Streams
    - Using DataFrames and DataSets API to Create Streaming DataFrames and DataSets
  - Window Transformations for Stateful and Stateless Operations

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

### Spark Machine Learning <- R Server
  - MLLib and Spark ML - Understanding API Patterns
  - Featurizing DataFrames using Transformers
  - Developing Machine Learning Pipelines with Spark ML
    - Cross-Validation and Hyperparameter Tuning
  - Training ML Models on Text Data: Tokenization, TF/IDF, and Topic Modeling with LDA
  - Using Evaluators to Evaluate Machine Learning Models
  - Unsupervised Learning and Clustering
  - Managing Models with ModelDB


#### R Server on Spark

  - Parallel External Memory Algorithms and Distributed Compute Contexts
  - Using and CRAN R Inside R Server Transforms
    + Distinctions and Considerations when Using CRAN R
  - Deploying R Functions and Models with `mrsdeploy`
    * Configuration and Roadmap
  - Deploying R Functions and Models with `azureml`  
  - Defining Your Own PEMA and UDFs with rxExec
  - Performance Comparisons to SparkML
    + Feature Comparisons

#### Notes

+ keep spark streaming/graphx as high level pieces
+ hands-on for streaming
  * structured streaming lab
+ need to all prerequisites together
+ daily quetsions
  10 or so questions

#### Structure

+ sparkml - pyspark or scala (1/4 day)
+ r server on spark (1/2 day)
+ ashish: dev skew [HDInsight sandbox]
  * still TBA, proposal
  * sandbox skew -> 
    - most workloads pkgd into single VM
    - very useful for trainings!
    - consider for examples
    - no r server on spark
+ auto-scale spark
  * might be ready for demo
  * keep it high level

