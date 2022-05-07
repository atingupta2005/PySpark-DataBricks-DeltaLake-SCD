# Day 1 - Python Basics

1)  Introduction

2)  Python Overview

3)  Features of Python

4)  Python Environment Set-up and Installation

5)  Jupyter Notebook Overview

6)  Python Basics

    a.  Basic Data Types

        i.  Numbers

        ii. Strings

        iii. Print Formatting

        iv. Booleans

    b.  Data structures

        i.  List

        ii. Tuple

        iii. Dictionary

        iv. Sets and sets operations

        v.  List comprehension

        vi. Collections

    c.  Comparison Operators

    d.  If, elif and else Statements

    e.  For and While Loops

    f.  Break and Continue statements

    g.  Range and Lists

7)  Python Built in functions

    a.  Range()

    b.  xrange()

    c.  Len()

    d.  Dir()

8)  Standard libraries

    a.  OS

    b.  SYS

    c.  CSV

    d.  Datetime

    e.  Time

9)  Functions and Lambda Expressions

    a.  Defining functions

    b.  Function calling

    c.  Positional arguments

    d.  Keyword arguments

    e.  Default arguments

    f.  Return statement in functions

    g.  Call-by-value

    h.  Call-by-reference

10) Functional programming

    a.  Lambda expressions

    b.  Map()

    c.  Reduce()

# Day 2 - Python Basics

11) File handling

    a.  Syntax

    b.  How to Open File

    c.  Read Lines

    d.  Write to an Existing File

    e.  Create a New File

    f.  Delete a File

12) Using NumPy Package in Python

    a.  Introduction to Numpy

    b.  Installation of Numpy

    c.  Numpy Arrays

    d.  Quick Note on Array Indexing

    e.  Numpy Array Indexing

    f.  Numpy Operations

    g.  Exercises

13) Using Pandas Package in Python

    a.  Introduction

    b.  Installation of Python

    c.  Series

    d.  DataFrames

    e.  Missing Data

    f.  Groupby

    g.  Merging Joining and Concatenating

    h.  Operations

    i.  Data Input and Output

14) Python Exceptions

    a.  Try/ Except/Else/Finally

    b.  Exceptions versus Syntax Errors

    c.  Raising an Exception

    d.  Assert

    e.  The AssertionError Exception

    f.  Python Built-in Exceptions

    g.  User-defined / Custom Exceptions

15) Regular Expressions

    a.  Introduction

    b.  Metacharacters

    c.  The search function

    d.  The match Function

    e.  Matching Versus Searching

    f.  Search and Replace

    g.  Examples

16) Logging in Python

    a.  Why Use the logging Module

    b.  Creating a Simple Logger

    c.  Logging Exceptions

    d.  Logging levels

# Day 3 - PySpark

17) What is Apache Spark

18) Apache Spark and Scala

19) Running Spark

    a.  Downloading Spark Locally

    b.  Launching Spark's Interactive Consoles

20) An Introduction to Apache Spark

    a.  Spark's Basic Architecture

    b.  Spark's Language APIs

    c.  Starting Spark

    d.  The SparkSession

    e.  DataFrames

        i.  Partitions

    f.  Transformations

        i.  Lazy Evaluation

    g.  Actions

    h.  Spark UI

    i.  An End-to-End Example

21) Spark's Toolset

22) Structured API

    a.  DataFrames and Datasets

    b.  Schemas

    c.  Overview of Structured Spark Types

        i.  DataFrames Versus Datasets

        ii. Columns

        iii. Rows

        iv. Spark Types

    d.  Overview of Structured API Execution

        i.  Logical Planning

        ii. Physical Planning

        iii. Execution

23) Basic Structured Operations

    a.  Schemas

    b.  Columns and Expressions

    c.  Records and Rows

    d.  DataFrame Transformations

# Day 4 - PySpark

24) Introducing Apache Parquet file format

    a.  What is Apache Parquet?

    b.  Parquet Format vs. CSV

    c.  Advantages of Parquet Columnar Storage

    d.  Primitive data types in Parquet format

    e.  Apache Parquet Spark Example

        i.  Spark Write DataFrame to Parquet file format

        ii. Spark Read Parquet file into DataFrame

        iii. Append to existing Parquet file

        iv. Using SQL queries on Parquet

        v.  Spark parquet partition -- Improving performance

        vi. Spark Read a specific Parquet partition

25) Aggregations

    a.  Aggregation Functions

        i.  count

        ii. min and max

        iii. sum

        iv. avg

    b.  Grouping

    c.  Window Functions

    d.  User-Defined Aggregation Functions

26) Joins

    a.  Join Expressions

    b.  Join Types

    c.  Inner Joins

    d.  Outer Joins

    e.  Left Outer Joins

    f.  Right Outer Joins

27) Data Sources

    a.  The Structure of the Data Sources API

    b.  CSV Files

    c.  JSON Files

    d.  Advanced I/O Concepts

        i.  Splittable File Types and Compression

        ii. Reading Data in Parallel

        iii. Writing Data in Parallel

        iv. Managing File Size

# Day 5 - PySpark

28) Spark SQL

    a.  What Is SQL?

    b.  How to Run Spark SQL Queries?

    c.  Catalog

    d.  Tables

    e.  Views

    f.  Select Statements

    g.  Databases

29) PySpark UDF Introduction

    a.  What is UDF?

    b.  Why do we need it?

30) Create PySpark UDF (User Defined Function)

    a.  Create a DataFrame

    b.  Create a Python function

    c.  Convert python function to UDF

31) Using UDF with DataFrame

    a.  Using UDF with DataFrame select()

    b.  Using UDF with DataFrame withColumn()

    c.  Registring UDF & Using it on SQL query

32) Resilient Distributed Datasets (RDDs)

    a.  What Are the Low-Level APIs?

    b.  About RDDs

        i.  Types of RDDs

        ii. When to Use RDDs?

    c.  Creating RDDs

    d.  Manipulating RDDs

    e.  Transformations

        i.  distinct

        ii. filter

        iii. map

        iv. sort

        v.  Random Splits

    f.  Actions

        i.  reduce

        ii. count

        iii. first

        iv. max and min

        v.  take

    g.  Saving Files

        i.  saveAsTextFile

        ii. SequenceFiles

        iii. Hadoop Files

    h.  Caching

# Day 6 - Advanced PySpark and Data Bricks

33) Distributed Shared Variables

    a.  Broadcast Variables

    b.  Accumulators

        i.  Basic Example

        ii. Custom Accumulators

34) Developing Spark Applications

    a.  Writing Spark Applications

    b.  The Development Process

    c.  Launching Applications

    d.  Configuring Applications

35) Performance Tuning

    a.  Indirect Performance Enhancements

    b.  Direct Performance Enhancements

36) Data Bricks

    a.  What is Azure Databricks?

    b.  Apache Spark-based analytics platform

    c.  Apache Spark in Azure Databricks

    d.  Fully managed Apache Spark clusters in the cloud

    e.  Databricks Runtime

37) Quickstart: Run a Spark job on Azure Databricks using the Azure
    > portal

    a.  Create an Azure Databricks workspace

    b.  Create a Spark cluster in Databricks

    c.  Run a Spark SQL job

38) Introduction to Databricks and Apache Spark

    a.  Introduction to databricks

    b.  Write your first Apache Spark Code

39) Databricks File System (DBFS)

    a.  DBFS root

    b.  Mount object storage to DBFS

    c.  Access DBFS

    d.  File upload interface

    e.  Databricks CLI

    f.  dbutils

    g.  DBFS API

    h.  Spark APIs

    i.  Local file APIs

# Day 7 - Delta Lake and SCD

40) Describe Azure Databricks Delta Lake architecture

    a.  Introduction

    b.  Describe bronze, silver, and gold architecture

    c.  Perform batch and stream processing

41) Delta Lake Example

    a.  Create a table

    b.  Read data

    c.  Update table data

    d.  Conditional update without overwrite

    e.  Read older versions of data using time travel

    f.  Write a stream of data to a table

    g.  Read a stream of changes from a table

42) SCD Type1 Implementation in Spark

    a.  What is SCD Type 1

    b.  SCD Type 1 in SQL and Python

    c.  Preparing Data Sets

    d.  INNER JOIN

    e.  LEFT OUTER JOIN

    f.  RIGHT OUTER JOIN

    g.  UNION ALL

    h.  functools reduce(...) function

    i.  SQL -- show tables

43) SCD Type2 Implementation in Spark

    a.  What is SCD type 2?

    b.  Star schema and SCD2 concept overview

    c.  SCD2 implementation challenge

    d.  Create SCD2 dataset

    e.  Manually find changes

    f.  Create new current records

    g.  Find previous current records to expire

    h.  Expire previous current records

    i.  Isolate unaffected records

    j.  Create new records

    k.  Updated table

    l.  Combine the datasets for new SCD2
