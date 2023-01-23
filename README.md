<h1 align="center">📔 Database develop RoadMap</h1>

Author is a database amateur, so the content is not authoritative, welcome to point out my error.

Since the database course is recommended, only good articles, papers or blogs are listed starting from part 3.
## List of Knowledge
- [List of Knowledge](#list-of-knowledge)
- [1. Description](#1-description)
- [2. Recommended Basic Course and Books](#2-recommended-basic-course-and-books)
  - [Pre-Skill](#pre-skill)
  - [2.1 Computer Organization and Design](#21-computer-organization-and-design)
    - [2.1.1 Courses](#211-courses)
    - [2.1.2 Books](#212-books)
  - [2.2 Computer Operating System](#22-computer-operating-system)
    - [2.2.1 Courses](#221-courses)
    - [2.2.2 Books](#222-books)
  - [2.3 Computer Network](#23-computer-network)
    - [2.3.1 Courses](#231-courses)
    - [2.3.2 Books](#232-books)
  - [2.4 Data Structure and Algorithmn](#24-data-structure-and-algorithmn)
    - [2.4.1 Courses](#241-courses)
    - [2.4.2 Books](#242-books)
  - [2.5 Algorithms Design and Analysis](#25-algorithms-design-and-analysis)
    - [2.5.1 Courses](#251-courses)
    - [2.5.2 Books](#252-books)
  - [2.6 Database](#26-database)
    - [2.6.1 Course](#261-course)
    - [2.6.2 Books](#262-books)
  - [2.6.3 Papers](#263-papers)
  - [2.7 Distributed System](#27-distributed-system)
- [3. SQL \& Relational Algebra](#3-sql--relational-algebra)
- [4. DDL \& DML](#4-ddl--dml)
- [5. Relational Model](#5-relational-model)
- [6. Storage \& Buffer](#6-storage--buffer)
  - [6.1 Storage](#61-storage)
  - [6.2 Buffer management](#62-buffer-management)
- [CS 15-445 课程 Lecture05](#cs-15-445-课程-lecture05)
- [7. Index structure](#7-index-structure)
  - [7.2 B+ Tree](#72-b-tree)
  - [7.3](#73)
- [8. Query Evaluation（Processing）](#8-query-evaluationprocessing)
- [9. Query Optimization](#9-query-optimization)
- [10. Transaction](#10-transaction)
- [11. Network](#11-network)
- [12. Serialization](#12-serialization)
- [13. Concurrency Control](#13-concurrency-control)
- [14. Crash Recovery](#14-crash-recovery)
- [15. NoSQL](#15-nosql)
- [16. NewSQL](#16-newsql)
- [17. Distributed Database](#17-distributed-database)
- [18. AI4DB and DB4AI (frontier tech)](#18-ai4db-and-db4ai-frontier-tech)
- [15. OLAP、OLTP、HTAP](#15-olapoltphtap)
  - [15.1 OLAP](#151-olap)
  - [15.2 OLTP](#152-oltp)
  - [15.3 HTAP](#153-htap)
- [16. Project Source Code Analysis](#16-project-source-code-analysis)
- [17. Mini-Project Labs](#17-mini-project-labs)


## 1. Description
This repo will not include knowledge about basic programming language. it mainly focus on direction of database kernal development. 

The tutorial will include content:
- Courses
- Blogs
- Papers
- Activities
- Talks

Ok, The repo include two language content：
- English Content
- Chinese Content.

If you have any good materials, welcome to submit a pull request for this repo.

Finally, I would like to thank the professor who provided the Course resource, papper resource Etc. Also thanks the blogger who provided the study notes. Thanks to all content resource providers.


## 2. Recommended Basic Course and Books
I will not update course notes and labs.
### Pre-Skill
- MIT [The Missing Semester of Your CS Education](https://missing.csail.mit.edu/)
- C/C++
- Go
- Rust

You only need to know a programming language.

### 2.1 Computer Organization and Design

#### 2.1.1 Courses

|University|ID|Name|Time|Comment|
|:--:|:--:|--|--|--|
|CMU|15-213/14-513/15-513|[Intro to Computer Systems(ICS)](https://www.cs.cmu.edu/afs/cs/academic/class/15213-f15/www/schedule.html)|Fall 2015|CS:APP3e|
|UC Berkeley|CS61C|[Great Ideas in Computer Architecture (Machine Structures)](https://www-inst.eecs.berkeley.edu//~cs61c/sp17/#resources)|Spring 2017|N/A|
|UC Berkeley|CS 152/252A|[Computer Architecture and Engineering](https://inst.eecs.berkeley.edu/~cs152/sp22/)|Spring 2022|N/A|
|N/A|N/A|Crash Course Computer Science||[bilibili地址](https://www.bilibili.com/video/BV1EW411u7th?p=1)|
|

#### 2.1.2 Books
- Reference Course Resources

### 2.2 Computer Operating System

#### 2.2.1 Courses

|University|ID|Name|Time|Comment|
|:--:|:--:|--|--|--|
|Stanford|CS110|[Principles of Computer Systems](http://web.stanford.edu/class/cs110/)|Winter 2022||
|MIT|6.828|[Operating System Engineering](https://pdos.csail.mit.edu/6.828/2018/schedule.html)|Fall 2018||
|UC Berkeley|CS162|[Operating Systems and System Programming](https://inst.eecs.berkeley.edu/~cs162/fa20/)|Fall 2020||
|MIT|6.033|http://web.mit.edu/6.033/www/index.shtml|N/A|covers four units of technical content: operating systems, networking, distributed systems, and security||
|

#### 2.2.2 Books
- Reference Course Resources
### 2.3 Computer Network
#### 2.3.1 Courses

|University|ID|Name|Time|Comment|
|:--:|:--:|--|--|--|
|Stanford|CS144|[Introduction to Computer Networking](https://cs144.github.io/)|Fall 2021||
|CMU|CS 15-744|[Computer Networks](https://www.cs.cmu.edu/~srini/15-744/S18/www/syllabus.html)|Spring 2018||
|中科大USTC|N/A|[计算机网络](https://www.bilibili.com/video/BV1JV411t7ow?p=1)|N/A|undergraduate stage|
|中科大USTC|N/A|[高级计算机网络](https://www.bilibili.com/video/BV1BL4y1J7vh?p=1)|N/A|postgraduate stage|
|

#### 2.3.2 Books
- Reference Course Resources

### 2.4 Data Structure and Algorithmn

#### 2.4.1 Courses
|University|ID|Name|Time|Comment|
|:--:|:--:|--|--|--|
|UC Berkeley|CS 61B|[Data Structures](http://fa20.datastructur.es/)|Fall 2020||
|CMU|CS 15-122|[Principles of Imperative Computation](http://www.cs.cmu.edu/~15122/schedule.shtml)|Spring 2023|Past Courses Page 404|
|CMU|CS 15-121|[Introduction Data Structures](http://www.cs.cmu.edu/~mjs/121/lectures.html)|Spring 2018||
|


#### 2.4.2 Books
- Reference Course Resources

### 2.5 Algorithms Design and Analysis

#### 2.5.1 Courses
|University|ID|Name|Time|Comment|
|:--:|:--:|--|--|--|
|UC Berkeley|UC Berkeley|[Efficient Algorithms and Intractable Problems](https://cs170.org/)|||
|MIT|6.006|[Introduction to Algorithms](https://ocw.mit.edu/courses/6-006-introduction-to-algorithms-spring-2020/pages/calendar/)|Spring 2020|Introduction to Algorithmns|
|CMU|CS 15-451/651|[Algorithm Design and Analysis](http://www.cs.cmu.edu/~15451-f21/schedule.html)|Fall 2021||
|CMU|CS 15-850|[Advanced Algorithms](http://www.cs.cmu.edu/afs/cs.cmu.edu/academic/class/15850-f20/www/)|Fall 2020||
|

#### 2.5.2 Books
- Reference Course Resources

### 2.6 Database

#### 2.6.1 Course

|University|ID|Name|Time|Comment|
|:--:|:--:|--|--|--|
|CMU|CS 15-445/645|[Database Systems](https://15445.courses.cs.cmu.edu/fall2022/)|Fall 2022|Instructor: [Andy Pavlo](https://www.cs.cmu.edu/~pavlo/)|
|UC Berkeley|CS 186|[Introduction to Database Systems](https://cs186berkeley.net/sp22/)|Spring 2022||
|Pennsylvania|CMPSC 431W|[Database Management Systems](http://yusanlin.com/cmpsc431w/lectures.html)|Fall 2015||
|Stanford|CS346|[Database System Implementation](https://web.stanford.edu/class/cs346/2015/)|Spring 2015||
|uwaterloo|CS 448/648|[Database Systems Implementation](https://cs.uwaterloo.ca/~david/cs448/lectures.html)|Winter 2009||
|CMU|CS 15-721|[Advanced Database Systems](https://15721.courses.cs.cmu.edu/spring2020/schedule.html)|Spring 2020|Instructor: [Andy Pavlo](https://www.cs.cmu.edu/~pavlo/)|
|CMU|CS 15-799|[Special Topics: Self-Driving Database Management Systems](https://15799.courses.cs.cmu.edu/spring2022/schedule.html)|Spring 2022|Instructor: [Andy Pavlo](https://www.cs.cmu.edu/~pavlo/)||
|uwaterloo|CS 856|[Distributed data management fundamentals (architectures, data placement, query optimization)](https://cs.uwaterloo.ca/~tozsu/courses/cs856/F02/lecture-1.pdf)<br>[Distributed transaction processing, concurrency control, recovery, interoperability](https://cs.uwaterloo.ca/~tozsu/courses/cs856/F02/lecture-2.pdf)|Fall 2002|Only need these two slides, nothing else|
|

#### 2.6.2 Books
- [Database System Concepts Seventh Edition](https://www.db-book.com/), by Silberschatz, Korth and Sudarshan 中文版：《数据库系统概念》

- [Database Management Systems](https://pages.cs.wisc.edu/~dbbook/), by Ramakrishnan and Gehrke 中文版：《数据库管理系统原理与设计》

- [Database Internals A Deep-Dive into How Distributed Data System Work](https://www.oreilly.com/library/view/database-internals/9781492040330/), by Alex Petrov 中文版：《数据库系统内幕》

- [Designing Data-Intensive Applications](https://martin.kleppmann.com/), by Martin Kleppmann

- [Database Design and Implementation](https://link.springer.com/book/10.1007/978-3-030-33836-7), by Edward Sciore

- [Database System Implementation](http://infolab.stanford.edu/~ullman/dbsi.html)， by Hector Garcia-Molina, Jeff Ullman, and Jennifer Widom 中文版：《数据库系统实现》
  - This book has been replaced by [Database Systems: The Complete Book](http://infolab.stanford.edu/~ullman/dscb.html)

- [Transaction Processing Concepts and Techniques](http://jimgray.azurewebsites.net/wics_99_tp/) by Jim Gray

- [Principles of Distributed Database Systems](https://cs.uwaterloo.ca/~tozsu/ddbook/), by M. Tamer Özsu and Patrick Valduriez 中文版：《分布式数据库系统原理》

- [nosql distilled a brief guide to the emerging world of polyglot persistence](https://bigdata-ir.com/wp-content/uploads/2017/04/NoSQL-Distilled.pdf), by Pramod J. Sadalage and Martin Fowler 中文版：《NoSQL精髓》

- [High Performance MySQL Third Edition](http://web-algarve.com/books/MySQL%20&%20PHP/high%20performance%20mysql%203rd%20edition.pdf), by Baron Schwartz, Peter Zaitsev, Vadim Tkachenko 中文版：《高性能MySQL》


- [MySQL High Availability: Tools for Building Robust Data Centers](http://web-algarve.com/books/MySQL%20&%20PHP/mysql%20high%20availability.pdf), by CharlesBell,MatsKindahl,LarsThalmann 中文版：《高可用MySQL:构建健壮的数据中心》

### 2.6.3 Papers
CS 15-721 Topics Papers


### 2.7 Distributed System
This Section is for distributed database.

|University|ID|Name|Time|Comment|
|:--:|:--:|--|--|--|
|MIT|6.824|[MIT Distributed Systems](http://nil.csail.mit.edu/6.824/2021/schedule.html)|Spring 2021|Golang|
|N/A|N/A|[Distributed Systems](https://www.distributedsystemscourse.com/)||
|Columbia University|COMS 4113|[Distributed Systems Fundamentals](https://systems.cs.columbia.edu/ds1-class/01-lectures/)||
|CMU|CS 15-440|[CMU Distributed Systems](http://www.cs.cmu.edu/~dga/15-440/F10/syllabus.html)||
|Princeton|COS 418|[Princeton Distributed Systems](https://www.cs.princeton.edu/courses/archive/fall19/cos418/schedule.html)|Fall 2019||
|Columbia University||[Advanced Distributed Systems](https://systems.cs.columbia.edu/ds2-class/01-papers/)|Research Papers|
|


## 3. SQL & Relational Algebra
- SQL 知识点：Book《Database System Conceptsm》Chapter3、Chapter4、Chapter5
- Relational Algebra 知识点：Book《Database System Conceptsm》Chapter6
- w3cSchools SQL: https://www.w3schools.com/sql/
- [Introduction of Relational Algebra in DBMS](https://www.geeksforgeeks.org/introduction-of-relational-algebra-in-dbms/)

- [Relational Algebra in DBMS: Operations with Examples](https://www.guru99.com/relational-algebra-dbms.html)

- slide : [Relational Algebra and SQL](https://www3.cs.stonybrook.edu/~kifer/Courses/cse532/slides/ch5.pdf)

- [SQL深入理解|关系代数、简单查询、连接](https://zhuanlan.zhihu.com/p/165365961)

- [SQL 与关系代数](https://rgb-24bit.github.io/blog/2019/sql-relational-algebra.html)

## 4. DDL & DML
- DDL : https://cloud.google.com/bigquery/docs/reference/standard-sql/data-definition-language
- DML : https://cloud.google.com/bigquery/docs/reference/standard-sql/dml-syntax

- [Difference Between DDL and DML in DBMS](https://www.guru99.com/difference-between-ddl-and-dml.html)


## 5. Relational Model
- WikiPedia : [Relational model](https://en.wikipedia.org/wiki/Relational_model)
- [Relational Data Model in DBMS | Database Concepts & Example](https://www.guru99.com/relational-data-model-dbms.html)
- [What is ER Modeling? Learn with Example](https://www.guru99.com/er-modeling.html)
- [ER (Entity Relationship) Diagram in DBMS](https://www.javatpoint.com/dbms-er-model-concept)

- [Relational Model in DBMS](https://www.scaler.com/topics/dbms/relational-model-in-dbms/)
  
- [数据库系统原理学习笔记（二）-数据库设计和ER图](https://blog.taielab.com/2018-09-30/database-system-principle-leannote-db-er-designer.html)

- [Understanding Relational Databases](https://www.digitalocean.com/community/tutorials/understanding-relational-databases)
## 6. Storage & Buffer
### 6.1 Storage
CS 15-445 课程 Lecture03、Lecture04

- [Storage 101 Series](https://www.red-gate.com/simple-talk/databases/sql-server/database-administration-sql-server/storage-101-welcome-to-the-wonderful-world-of-storage/)
  - [Storage 101: Understanding the Hard-Disk Drive](https://www.red-gate.com/simple-talk/databases/sql-server/database-administration-sql-server/storage-101-understanding-the-hard-disk-drive/)

  - [Storage 101: Understanding the NAND Flash Solid State Drive](https://www.red-gate.com/simple-talk/databases/sql-server/database-administration-sql-server/storage-101-understanding-the-nand-flash-solid-state-drive/)

  - [Storage 101: RAID](https://www.red-gate.com/simple-talk/databases/sql-server/database-administration-sql-server/storage-101-raid/)

- [RAID](https://www.javatpoint.com/dbms-raid)

- [RAID and Its Impact on your SQL Performance](https://www.sqlservercentral.com/articles/raid-and-its-impact-on-your-sql-performance)

- [Importance of RAID in Databases](https://www.sqlservercurry.com/2013/09/importance-of-raid-in-databases.html)


### 6.2 Buffer management
CS 15-445 课程 Lecture05
- 


## 7. Index structure


### 7.2 B+ Tree


### 7.3 


## 8. Query Evaluation（Processing）



## 9. Query Optimization
- [Top 10 SQL Query Optimization Tips to Improve Database Performance](https://www.mantralabsglobal.com/blog/sql-query-optimization-tips/), by Avishek Singh
  
- 

## 10. Transaction


## 11. Network


## 12. Serialization


## 13. Concurrency Control


## 14. Crash Recovery

## 15. NoSQL

## 16. NewSQL

## 17. Distributed Database
- Oracle7 Server Concepts Manual : [Distributed Databases](https://docs.oracle.com/cd/A57673_01/DOC/server/doc/SCN73/ch21.htm)
- [Spanner: Google's Globally-Distributed Database](https://www.usenix.org/system/files/conference/osdi12/osdi12-final-16.pdf)

## 18. AI4DB and DB4AI (frontier tech)
- University of Magdeburg slides:
  - slide 01 : https://www.dbse.ovgu.de/en/-p-578-EGOTEC-35lsmf8qh52t9v3rhrjdojrd46/_/5_ai-1.pdf
  - slide 02 : https://www.dbse.ovgu.de/-p-578/_/5_ai-2.pdf
- Tsinghua University databaseGroup Github : https://github.com/TsinghuaDatabaseGroup/AIDB
- Tsinghua & MIT Paper : https://dbgroup.cs.tsinghua.edu.cn/ligl/papers/sigmod21-tutorial-paper.pdf
- openGauss Blog : [openGauss AI4DB and DB4AI](https://blog.opengauss.org/en/post/2022/opengauss-ai4db-and-db4ai/)
- MIT databaseGroup : http://dsg.csail.mit.edu/mlforsystems/papers/
- Blogger Github : https://github.com/LumingSun/ML4DB-paper-list

## 15. OLAP、OLTP、HTAP

### 15.1 OLAP
OnLine Analytical Processing
- [An Overview of Data Warehousing and OLAP Technology](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/sigrecord.pdf)

### 15.2 OLTP
Online Transaction Processing


### 15.3 HTAP
Hybrid Transactional/Analytical Processing

- [A Common Database Approach for OLTP and OLAP Using an In-Memory Column DataBase](http://www.sigmod09.org/images/sigmod1ktp-plattner.pdf)

- PingCAP : [How We Build an HTAP Database That Simplifies Your Data Platform](https://www.pingcap.com/blog/how-we-build-an-htap-database-that-simplifies-your-data-platform/)

- StoneDB 文章
  - [什么是真正的HTAP？（一）背景篇](https://zhuanlan.zhihu.com/p/542008685)
  - [什么是真正的 HTAP ？（二）挑战篇](https://zhuanlan.zhihu.com/p/544938116)


## 16. Project Source Code Analysis

|ID|Database|DataBase Type|Blog|Github|
|:--:|--|--|--|--|
|1|SQlite||[SQlite源码分析](https://huili.github.io/index.html)|https://github.com/sqlite/sqlite|
|2|LevelDB|fast key-value storage library|[LevelDB 源码剖析](https://www.zhihu.com/column/c_1282795241104465920)|https://github.com/google/leveldb|
|3|PolarDB-X|cloud native distributed SQL Database|[PolarDB-X 源码解读](https://www.zhihu.com/column/c_1449680469579640832)|https://github.com/polardb/polardbx-sql|
|4|OceanBase|distributed relational database ||https://github.com/oceanbase/oceanbase|
|5|TiDB|cloud-native, distributed, MySQL-Compatible database|[TiDB源码阅读分析](https://github.com/pingcap/presentations/blob/master/hackathon-2019/reference-document-of-hackathon-2019.md)|https://github.com/pingcap/tidb|

taobao MySQL 数据库内核月报：http://mysql.taobao.org/monthly/

## 17. Mini-Project Labs
- DeepDB : https://github.com/deepbodra97/Database-System-Implementation
- Mini-OB : https://open.oceanbase.com/activities/4921877

- CS 15-445 Labs