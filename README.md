<h1 align="center">📔 Database Kernal develop RoadMap</h1>

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
    - [2.7.1 Courses](#271-courses)
    - [2.7.2 Books](#272-books)
    - [2.7.3 Papers](#273-papers)
    - [2.7.4 Blogs](#274-blogs)
- [3. SQL \& Relational Algebra](#3-sql--relational-algebra)
- [4. DDL \& DML](#4-ddl--dml)
- [5. Relational Model](#5-relational-model)
- [6. Storage management](#6-storage-management)
  - [6.1 Buffer Pool](#61-buffer-pool)
  - [6.2 Index](#62-index)
  - [6.3 B+ Tree](#63-b-tree)
  - [6.4 B- Tree](#64-b--tree)
  - [6.5 Hash table](#65-hash-table)
  - [6.6 LSM Tree](#66-lsm-tree)
  - [6.7 Storage engine](#67-storage-engine)
- [7. Query Processing](#7-query-processing)
- [8. SQL Parser](#8-sql-parser)
  - [8.1 Syntax Check](#81-syntax-check)
  - [8.2 Semantic Check](#82-semantic-check)
  - [8.3 Shared Pool Check](#83-shared-pool-check)
  - [8.4 Actions](#84-actions)
- [9. SQL Executor](#9-sql-executor)
- [9. SQL Optimization](#9-sql-optimization)
  - [9.1 SQL Query Optimization](#91-sql-query-optimization)
  - [9.2 Indexes Optimization](#92-indexes-optimization)
  - [9.3 Table Optimization](#93-table-optimization)
  - [9.4 Buffer Cache Optimization](#94-buffer-cache-optimization)
  - [9.5 Storage Optimization](#95-storage-optimization)
  - [9.7 table Structure Optimization](#97-table-structure-optimization)
    - [9.7.1 data reduction](#971-data-reduction)
    - [9.7.2 data  partition](#972-data--partition)
  - [9.8 Optimizer](#98-optimizer)
  - [9.9 SQL调优博客List](#99-sql调优博客list)
- [10. Transaction management](#10-transaction-management)
- [Lock manager](#lock-manager)
- [11. Network](#11-network)
- [12. Serialization](#12-serialization)
- [13. Concurrency Control](#13-concurrency-control)
- [14. Crash Recovery management](#14-crash-recovery-management)
- [15. NoSQL](#15-nosql)
- [16. NewSQL](#16-newsql)
- [17. Distributed \& Paralleled](#17-distributed--paralleled)
- [15. OLAP、OLTP、HTAP](#15-olapoltphtap)
  - [15.1 OLAP](#151-olap)
  - [15.2 OLTP](#152-oltp)
  - [15.3 HTAP](#153-htap)
- [16. Graph Database](#16-graph-database)
  - [16.1 Courses](#161-courses)
  - [16.2 Books](#162-books)
  - [16.3 Papers](#163-papers)
  - [16.4 Blogs](#164-blogs)
- [16. Project Source Code Analysis](#16-project-source-code-analysis)
- [17. Mini-Project Labs](#17-mini-project-labs)
- [18. AI4DB and DB4AI (frontier tech)](#18-ai4db-and-db4ai-frontier-tech)
- [Database Retrospective](#database-retrospective)


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


#### 2.3.2 Books
- Reference Course Resources

### 2.4 Data Structure and Algorithmn

#### 2.4.1 Courses
|University|ID|Name|Time|Comment|
|:--:|:--:|--|--|--|
|UC Berkeley|CS 61B|[Data Structures](http://fa20.datastructur.es/)|Fall 2020||
|CMU|CS 15-122|[Principles of Imperative Computation](http://www.cs.cmu.edu/~15122/schedule.shtml)|Spring 2023|Past Courses Page 404|
|CMU|CS 15-121|[Introduction Data Structures](http://www.cs.cmu.edu/~mjs/121/lectures.html)|Spring 2018||



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
|N/A|N/A|[Let's Build a Simple Database: Writing a sqlite clone from scratch in C](https://cstack.github.io/db_tutorial/)||Thanks to cstack|


#### 2.6.2 Books
- [fundamentals of database systems 7th edition solutions](https://amirsmvt.github.io/Database/Static_files/Fundamental_of_Database_Systems.pdf), by Ramez Elmasri, Shamkant B. Navathe

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

#### 2.6.3 Papers
- CS 15-721 Topics Papers

- Paper 2017 : [How to Build a Non-Volatile Memory Database Management System](https://db.cs.cmu.edu/papers/2017/p1753-arulraj.pdf)

- Aticle : [Main Memory Database Systems](http:/justinlevandoski.org/papers/fnt-mmdb.pdf)

- Paper thesis 2018 : [The Design and Implementation of a Non-Volatile Memory Database Management System](https://faculty.cc.gatech.edu/~jarulraj/papers/2018.thesis.pdf)

- harvard Aticle : [The Design and Implementation of Modern Column-Oriented Database Systems](https://stratos.seas.harvard.edu/files/stratos/files/columnstoresfntdbs.pd)

- [In-Memory Database Systems - A Paradigm Shift](https://citeseerx.ist.psu.edu/document?repid=rep1&type=pdf&doi=f0c37c844e331bea681ff7e1a981d8e053f2a753)

### 2.7 Distributed System
This Section is for distributed database.

- [Notes on Distributed Systems for Young Bloods](https://www.somethingsimilar.com/2013/01/14/notes-on-distributed-systems-for-young-bloods/)
#### 2.7.1 Courses

|University|ID|Name|Time|Comment|
|:--:|:--:|--|--|--|
|MIT|6.824|[MIT Distributed Systems](http://nil.csail.mit.edu/6.824/2021/schedule.html)|Spring 2021|Golang|
|N/A|N/A|[Distributed Systems](https://www.distributedsystemscourse.com/)||
|Columbia University|COMS 4113|[Distributed Systems Fundamentals](https://systems.cs.columbia.edu/ds1-class/01-lectures/)||
|CMU|CS 15-440|[CMU Distributed Systems](http://www.cs.cmu.edu/~dga/15-440/F10/syllabus.html)||
|Princeton|COS 418|[Princeton Distributed Systems](https://www.cs.princeton.edu/courses/archive/fall19/cos418/schedule.html)|Fall 2019|Golang|
|Columbia University||[Advanced Distributed Systems](https://systems.cs.columbia.edu/ds2-class/01-papers/)|Research Papers|
|MIT|6.852|[MIT Distributed Algorithms](http://courses.csail.mit.edu/6.852/08/lecture.html)||
|ETHZ|N/A|[Principles of Distributed Computing (lecture collection)](https://disco.ethz.ch/courses/podc_allstars/)||
|Stanford|CS244b|[Distributed Systems](http://www.scs.stanford.edu/20sp-cs244b/)|Spring 2020|
|Washington|CSE 490H|[Distributed Systems](https://courses.cs.washington.edu/courses/cse490h/11wi/#projects)|Autumn 2010|

#### 2.7.2 Books
- [Distributed Systems 3rd edition (2017)](https://www.distributed-systems.net/index.php/books/ds3/)
- [Distributed systems for fun and profit](http://book.mixu.net/distsys/)
- [Data-Intensive Text Processing with MapReduce](http://lintool.github.io/MapReduceAlgorithms/MapReduce-book-final.pdf) 
- [Distributed Systems: Principles and Paradigms](https://vowi.fsinf.at/images/b/bc/TU_Wien-Verteilte_Systeme_VO_%28G%C3%B6schka%29_-_Tannenbaum-distributed_systems_principles_and_paradigms_2nd_edition.pdf)
- [Principles of Computer System Design](https://ocw.mit.edu/courses/res-6-004-principles-of-computer-system-design-an-introduction-spring-2009/pages/online-textbook/)
- [designing data-intensive applications](https://bayanbox.ir/view/5162266560232218675/Designing-Data-Intensive-Applications.pdf) , DDIA
- [Introduction to Distributed Algorithms](https://ki.pwr.edu.pl/lemiesz/info/Tel.pdf)


#### 2.7.3 Papers
- Reference :
  - http://reiddraper.github.io/distreader/
  - MIT6.824 : http://nil.csail.mit.edu/6.824/2015/schedule.html
  - http://henryr.github.io/distributed-systems-readings/

- Causality
  - Paper 1978 : [Time, Clocks, and the Ordering of Events in a Distributed Syste](https://lamport.azurewebsites.net/pubs/time-clocks.pdf)
  - Paper 2008 : [Interval Tree Clocks: A Logical Clock for Dynamic Systems](https://gsd.di.uminho.pt/members/cbm/ps/itc2008.pdf) , ITC2008

- Consistency
  - [Brewer's Conjecture and the Feasibility of Consistent, Available, Partition-Tolerant Web Services](https://users.ece.cmu.edu/~adrian/731-sp04/readings/GL-cap.pdf)

- Consensus
  - [consensus-bridging-theory-and-practice](https://web.stanford.edu/~ouster/cgi-bin/papers/OngaroPhD.pdf)
  - [Raft Refloated: Do We Have Consensus?](https://people.csail.mit.edu/malte/pub/papers/2015-osr-raft.pdf)
  - [The Part Time Parliament](https://lamport.azurewebsites.net/pubs/lamport-paxos.pdf)
  - [Memory Coherence in Shared Virtual Memory Systems](http://nil.csail.mit.edu/6.824/2015/papers/li-dsm.pdf)
  - [TreadMarks: Distributed Shared Memory on Standard WorkStations and Operating Systems](http://nil.csail.mit.edu/6.824/2015/papers/keleher-treadmarks.pdf)
  - [Managing Update Conflicts in Bayou, a Weakly Connected Replicated Storage System](http://nil.csail.mit.edu/6.824/2015/papers/bayou-conflicts.pdf)
  - [Resolving File Conflicts in the Ficus File System](http://nil.csail.mit.edu/6.824/2015/papers/ficus.pdf)
  - [Consistency Analysis in Bloom: a CALM and Collected Approach](https://people.ucsc.edu/~palvaro/cidr11.pdf)
  - Paper 2009 : [Object Storage on CRAQ High-throughput chain replication for read-mostly workloads](https://www.usenix.org/legacy/event/usenix09/tech/full_papers/terrace/terrace.pdf) , USENIX2009
  - [Distributed SQLite: a replicated SQLite service powered by RAFT](http://www.scs.stanford.edu/20sp-cs244b/projects/Distributed%20SQLite.pdf)

- Data Stores
  - [Simplified Harp File System](http://www.scs.stanford.edu/20sp-cs244b/projects/Simplified%20Harp%20File%20System.pdf)
  - [Google File System 2.0: A Modern Design and Implementation](http://www.scs.stanford.edu/20sp-cs244b/projects/GFS%202_0.pdf)
  - [Replication in the Harp File System](http://nil.csail.mit.edu/6.824/2015/papers/bliskov-harp.pdf)
  - [Simplified GFS](http://www.scs.stanford.edu/20sp-cs244b/projects/Simplified%20GFS.pdf)
  - [Chunky: a distributed GFS-based file store](http://www.scs.stanford.edu/20sp-cs244b/projects/Chunky.pdf)
  - [Append-only Datastore](http://www.scs.stanford.edu/20sp-cs244b/projects/Append-only%20Datastore.pdf)
  - [Key-Value Store Using Chain Replication](http://www.scs.stanford.edu/20sp-cs244b/projects/Key-Value%20Store%20Using%20Chain%20Replication.pdf)
  - [ACID Compliant Distributed Key-Value Store](http://www.scs.stanford.edu/20sp-cs244b/projects/ACID%20Compliant%20Distributed%20Key-Value%20Store.pdf)
  - [RAFT based Key-Value Store with Transaction Support](http://www.scs.stanford.edu/20sp-cs244b/projects/RAFT%20based%20Key-Value%20Store%20with%20Transaction%20Support.pdf)

- General
  - Paper 2010 : [The Declarative Imperative: Experiences and Conjectures in Distributed Logic](https://dsf.berkeley.edu/papers/sigrec10-declimperative.pdf) , SIGMOD2010
  - Paper 2004 : [MapReduce: Simplified Data Processing on Large Clusters](http://static.googleusercontent.com/media/research.google.com/en/us/archive/mapreduce-osdi04.pdf) , OSDI2004
  - Paper : [Availability in Globally Distributed Storage Systems](http://static.googleusercontent.com/media/research.google.com/en/us/pubs/archive/36737.pdf)

- Fault Tolerance
  - [Remus: High Availability via Asynchronous Virtual Machine Replication](http://nil.csail.mit.edu/6.824/2015/papers/remus.pdf)
  - [Paxos Made Simple](http://nil.csail.mit.edu/6.824/2015/papers/paxos-simple.pdf) , ACM SIGACT News 2001
  - [In Search of an Understandable Consensus Algorithm](http://nil.csail.mit.edu/6.824/2015/papers/raft-atc14.pdf)
  - [Harvest, Yield, and Scalable Tolerant Systems](https://radlab.cs.berkeley.edu/people/fox/static/pubs/pdf/c18.pdf)
  - [Paxos Made Moderately Complex](https://paxos.systems/)
  - [Distributed Multi-Agent Consensus for Fault Tolerant Decision Making](http://www.scs.stanford.edu/20sp-cs244b/projects/Multi-Agent%20Consensus%20for%20Decision%20Making.pdf)

  
- Atomicity
  - [The Akamai Network: A Platform for High-Performance
Internet Applications](http://nil.csail.mit.edu/6.824/2015/papers/akamai.pdf)
  - Argus : [DISTRIBUTED PROGRAMMING IN ARGUS](http://nil.csail.mit.edu/6.824/2015/papers/argus88.pdf)
  - Thor : [Efficient Optimistic Concurrency Control
Using Loosely Synchronized Clocks](http://nil.csail.mit.edu/6.824/2015/papers/thor95.pdf)

- Application
  - Paper 2003 : [The Google File System](http://static.googleusercontent.com/media/research.google.com/en/us/archive/gfs-sosp2003.pdf) , SOSP2003
  - Paper 2003 : [Bigtable: A Distributed Storage System for Structured Data](http://static.googleusercontent.com/media/research.google.com/en//archive/bigtable-osdi06.pdf) , OSDI2006
  - Paper 2007 : [Dynamo: Amazon’s Highly Available Key-value Store ](https://www.allthingsdistributed.com/files/amazon-dynamo-sosp2007.pdf) , SOSP2007
  - [Peer-to-Peer Note Taking App](http://www.scs.stanford.edu/20sp-cs244b/projects/Peer-to-Peer%20Note%20Taking%20App.pdf)
  - [factoryOS: A Distributed and Self-Organizing Planning System in a Supply-Chain Context](http://www.scs.stanford.edu/20sp-cs244b/projects/factoryOS.pdf)
  - [Megastore: Providing Scalable, Highly Available Storage for Interactive Services](https://courses.cs.washington.edu/courses/cse490h/11wi/CSE490H_files/cloud.megastore.pdf) , CIDR 2011
  - [PNUTS: Yahoo!’s Hosted Data Serving Platform](https://courses.cs.washington.edu/courses/cse490h/11wi/CSE490H_files/cooper-pnuts.pdf) , VLDB 2008


#### 2.7.4 Blogs
- Oracle7 Server Concepts Manual : [Distributed Databases](https://docs.oracle.com/cd/A57673_01/DOC/server/doc/SCN73/ch21.htm)
- [Replication, atomicity and order in distributed systems](http://afeinberg.github.io/2011/06/17/replication-atomicity-and-order-in-distributed-systems.html)
- [Distributed Systems and the End of the API](https://writings.quilt.org/2014/05/12/distributed-systems-and-the-end-of-the-api/)
- [MIT Theory of Distributed Systems (TDS)](http://groups.csail.mit.edu/tds/)
- [分布式系统学习资料汇总](https://www.qtmuniao.com/2021/05/16/distributed-system-material/) , Blogger : 木鸟杂记
- [分布式系统(Distributed System)资料](https://github.com/ty4z2008/Qix/blob/master/ds.md) , Github Blogger : ty4z2008
- [Notes on Paxos](https://matklad.github.io/2020/11/01/notes-on-paxos.html)
- [Understanding Paxos](https://people.cs.rutgers.edu/~pxk/417/notes/paxos.html)
- [Paxos 学习笔记1 - Basic Paxos](https://www.cnblogs.com/ljx-null/p/15940762.html)
- [Paxos 学习笔记2 - Multi-Paxos](https://www.cnblogs.com/ljx-null/p/15940785.html)
- [Raft 学习笔记1 - 领导人选举和日志复制](https://www.cnblogs.com/ljx-null/p/15940921.html)

- [Raft协议详解](https://zhuanlan.zhihu.com/p/27207160)

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

- [MySQL · 源码分析 · 原子DDL的实现过程](http://mysql.taobao.org/monthly/2018/03/02/)

- [MySQL · 源码分析 · 8.0 原子DDL的实现过程【续】](http://mysql.taobao.org/monthly/2018/07/02/)

- [MySQL · 源码分析 · DDL log与原子DDL的实现](http://mysql.taobao.org/monthly/2021/07/05/)

- [PolarDB · 优化改进 · DDL的优化和演进](http://mysql.taobao.org/monthly/2021/01/03/)

- [PolarDB · 功能特性 · 非阻塞DDL](http://mysql.taobao.org/monthly/2022/10/01/)

- [MySQL · 源码分析 · 8.0 · DDL的那些事](http://mysql.taobao.org/monthly/2020/05/05/)

- [X-Engine · 引擎特性 · 并行DDL](http://mysql.taobao.org/monthly/2021/01/07/)

## 5. Relational Model
- WikiPedia : [Relational model](https://en.wikipedia.org/wiki/Relational_model)
- [Relational Data Model in DBMS | Database Concepts & Example](https://www.guru99.com/relational-data-model-dbms.html)
- [What is ER Modeling? Learn with Example](https://www.guru99.com/er-modeling.html)
- [ER (Entity Relationship) Diagram in DBMS](https://www.javatpoint.com/dbms-er-model-concept)

- [Relational Model in DBMS](https://www.scaler.com/topics/dbms/relational-model-in-dbms/)
  
- [数据库系统原理学习笔记（二）-数据库设计和ER图](https://blog.taielab.com/2018-09-30/database-system-principle-leannote-db-er-designer.html)

- [Understanding Relational Databases](https://www.digitalocean.com/community/tutorials/understanding-relational-databases)

- [Understanding the Enhanced ER Model Simplified 101](https://hevodata.com/learn/enhanced-er-model/)

- [Data Model Relationships 101: Simplified Guide for Beginners](https://hevodata.com/learn/data-model-relationships/)

- [9 ER Model Tools to use in 2023: A Comprehensive List](https://hevodata.com/learn/er-model-tools/)

## 6. Storage management
CS 15-445 课程 Lecture03、Lecture04

- [Managing Database Storage Structures](https://docs.oracle.com/en/database/oracle/oracle-database/19/admqs/managing-database-storage-structures.html#GUID-1C4BBF52-BBD8-4F37-92DD-80D414A75B59)

- [Some study on database storage internals](https://kousiknath.medium.com/data-structures-database-storage-internals-1f5ed3619d43)

- [Storage 101 Series](https://www.red-gate.com/simple-talk/databases/sql-server/database-administration-sql-server/storage-101-welcome-to-the-wonderful-world-of-storage/)
  - [Storage 101: Understanding the Hard-Disk Drive](https://www.red-gate.com/simple-talk/databases/sql-server/database-administration-sql-server/storage-101-understanding-the-hard-disk-drive/)

  - [Storage 101: Understanding the NAND Flash Solid State Drive](https://www.red-gate.com/simple-talk/databases/sql-server/database-administration-sql-server/storage-101-understanding-the-nand-flash-solid-state-drive/)

  - [Storage 101: RAID](https://www.red-gate.com/simple-talk/databases/sql-server/database-administration-sql-server/storage-101-raid/)

- [RAID](https://www.javatpoint.com/dbms-raid)

- [RAID and Its Impact on your SQL Performance](https://www.sqlservercentral.com/articles/raid-and-its-impact-on-your-sql-performance)

- [Importance of RAID in Databases](https://www.sqlservercurry.com/2013/09/importance-of-raid-in-databases.html)

- Microsoft Research Paper : [Faster: A Concurrent Key-Value Store with In-Place Updates](https://www.microsoft.com/en-us/research/uploads/prod/2018/03/faster-sigmod18.pdf), SIGMOD2018

### 6.1 Buffer Pool
- CS 15-445 课程 Lecture05

- [MySQL · 性能优化· InnoDB buffer pool flush策略漫谈](http://mysql.taobao.org/monthly/2015/02/01/)

- [MySQL · 引擎特性 · InnoDB Buffer Pool 浅析](http://mysql.taobao.org/monthly/2020/02/02/)

- [MySQL · 引擎特性 · Buffer Pool 漫谈](http://mysql.taobao.org/monthly/2019/07/03/)

- [MySQL · 引擎特性 · InnoDB Buffer Pool](http://mysql.taobao.org/monthly/2017/05/01/)

- [MySQL · 引擎特性 · InnoDB Buffer Page 生命周期](http://mysql.taobao.org/monthly/2020/08/04/)

- [InnoDB 的 Buffer Pool 分析](https://leviathan.vip/2018/12/18/InnoDB%E7%9A%84BufferPool%E5%88%86%E6%9E%90/)


### 6.2 Index
- wikiPedia : [Database index](https://en.wikipedia.org/wiki/Database_index)

- Google Cloud docs : [Indexes](https://cloud.google.com/datastore/docs/concepts/indexes)

- [Database Indexes Explained](https://www.essentialsql.com/what-is-a-database-index/)
- [An in-depth look at Database Indexing](https://www.freecodecamp.org/news/database-indexing-at-a-glance-bb50809d48bd/)


- [Database Index: An Introduction for Beginners](https://www.makeuseof.com/database-index-beginners/)

- [Indexing in DBMS: What is, Types of Indexes with EXAMPLES](https://www.guru99.com/indexing-in-database.html)

- [Database · 最佳实践 · 内存索引指南](http://mysql.taobao.org/monthly/2021/01/04/)

- [MongoDB · 特性分析 · 索引原理](http://mysql.taobao.org/monthly/2016/07/05/)

- [MongoDB · 引擎特性 · MongoDB索引原理](http://mysql.taobao.org/monthly/2018/09/06/)

- [Sparse Indexes（稀疏索引）](https://www.mongodb.com/docs/manual/core/index-sparse/)

- [MySQL · 引擎特性 · 二级索引分析](http://mysql.taobao.org/monthly/2020/01/01/)

- [MySQL · 源码阅读 · 创建二级索引](http://mysql.taobao.org/monthly/2020/11/03/)


### 6.3 B+ Tree

- wikiPedia : [B+ tree](https://en.wikipedia.org/wiki/B%2B_tree)

- CS 186 Spring notes pdf : [B+ tree](https://cs186berkeley.net/sp22/resources/static/notes/n04-B+Trees.pdf)

- University of Utah sliede : [Database Systems Index: B+ Tree](https://www.cs.bu.edu/~gkollios/cs660f19/Slides/treeindex.pdf)

- [implement a B+ Tree index file](https://inst.eecs.berkeley.edu/~cs186/fa04/btree_html)

- Paper 2004 : [Query and Update Efficient B-Tree Based Indexing of Moving Object](https://www.vldb.org/conf/2004/RS20P3.PDF)

- [MySQL · 引擎特性 · B+树并发控制机制的前世今生](http://mysql.taobao.org/monthly/2018/09/01/)

- [Innodb 中的 Btree 实现 (一) · 引言 & insert 篇](http://mysql.taobao.org/monthly/2022/12/03/)

- [POLARDB · 理论基础 · 敢问路在何方 — 论B+树索引的演进方向（上）](http://mysql.taobao.org/monthly/2018/11/01/)

- [POLARDB · 性能优化 · 敢问路在何方 — 论B+树索引的演进方向（中）](http://mysql.taobao.org/monthly/2019/02/01/)

- [MySQL · 源码分析 · innodb 空间索引实现](http://mysql.taobao.org/monthly/2022/08/04/)


### 6.4 B- Tree
- 课程：《Let's Build a Simple Database》
  - [Part 7 - Introduction to the B-Tree](https://cstack.github.io/db_tutorial/parts/part7.html)
  - [Part 8 - B-Tree Leaf Node Format](https://cstack.github.io/db_tutorial/parts/part8.html)

- [B- Tree Datastructure](http://www.btechsmartclass.com/data_structures/b-trees.html)

- [B- Trees : Software Design Using C++](https://cis.stvincent.edu/html/tutorials/swd/btree/btree.html)

- Paper 2010 , [Efficient B-tree Based Indexing for Cloud Data Processing](https://www.comp.nus.edu.sg/~ooibc/vldb10-cgindex.pdf), VLDB, National University of Singapore & IBM Watson Research Center

- [Database · 理论基础 · 高性能B-tree索引](http://mysql.taobao.org/monthly/2020/05/02/)
### 6.5 Hash table
- wikipedia : [Hash table](https://en.wikipedia.org/wiki/Hash_table)

- CMU CS15-445 slide : [Hash table slide](https://15445.courses.cs.cmu.edu/fall2020/slides/06-hashtables.pdf)

- GAtech.edu slide : [Hash table & Extendible Hash & Linear Hash](https://faculty.cc.gatech.edu/~jarulraj/courses/4420-f20/slides/13-hash-tables.pdf)

- Blog : [An Introduction to B-Tree and Hash Indexes in PostgreSQL](https://www.sentryone.com/blog/introduction-to-b-tree-and-hash-indexes-in-postgresql)

- [Extendible Hashing (Dynamic approach to DBMS)](https://www.geeksforgeeks.org/extendible-hashing-dynamic-approach-to-dbms/)

- [Extendible hashing for COSC 311](https://emunix.emich.edu/~shaynes/Papers/ExtendibleHashing/extendibleHashing.html)

### 6.6 LSM Tree
- [What is a LSM Tree?](https://dev.to/creativcoder/what-is-a-lsm-tree-3d75)

- [Log Structured Merge Trees](https://medium.com/swlh/log-structured-merge-trees-9c8e2bea89e8)

- slide : [Log Structured Merge Tree](https://lrita.github.io/images/posts/database/lsmtree-170129180333.pdf), thanks to Pinglei Guo

- Paper : [The Log-Structured Merge-Tree (LSM-Tree)](https://www.cs.umb.edu/~poneil/lsmtree.pdf)

- AlibabaCloud Community Blog : [Starting from Zero: Build an LSM Database with 500 Lines of Code](https://www.alibabacloud.com/blog/starting-from-zero-build-an-lsm-database-with-500-lines-of-code_598114)

- [B-Tree vs Log-Structured Merge-Tree](https://tikv.github.io/deep-dive-tikv/key-value-engine/B-Tree-vs-Log-Structured-Merge-Tree.html)

### 6.7 Storage engine
- [The Beginner’s Guide to MySQL Storage Engines](https://www.sisense.com/blog/beginners-guide-to-mysql-storage-engines/)

- [MySQL Storage Engines](https://www.w3resource.com/mysql/mysql-storage-engines.php)

- MySQL 8.0  docs : [Chapter 15 The InnoDB Storage Engine](https://dev.mysql.com/doc/refman/8.0/en/innodb-storage-engine.html)

- MySQL 8.0  docs : [Chapter 16 Alternative Storage Engines](https://dev.mysql.com/doc/refman/8.0/en/storage-engines.html)

- [Hybrid storage engine for geospatial data using NoSQL and SQL paradigms](https://www.scielo.sa.cr/scielo.php?script=sci_arttext&pid=S0379-39822021000100040)

- Oracle docs : [Chapter 13. Storage Engines](https://docs.oracle.com/cd/E19078-01/mysql/mysql-refman-5.0/storage-engines.html)

- Paper 2021 : Designing a persistent-memory-native storage engine for SQL database systems , , IEEE NVMSA 2021
  - Paper : https://nvmsa2021.github.io/paper/NVMSA_2021_Session_5-2_paper.pdf
  - Slide : https://nvmsa2021.github.io/slides/NVMSA_2021_Session_5-2_slides.pdf

- [MongoDB · 特性分析 · MMAPv1 存储引擎原理](http://mysql.taobao.org/monthly/2016/03/02/)

## 7. Query Processing
- [Distributed Query Processing (DQP)](https://ogsa-dai.sourceforge.net/documentation/ogsadai4.0/ogsadai4.0-gt/DQPPart.html)

- Database SQL Tuning Guide : [3 SQL Processing](https://docs.oracle.com/database/121/TGSQL/tgsql_sqlproc.htm#TGSQL175)

## 8. SQL Parser

- [SQL Parser API](https://www.sqlparser.com/)
- [Examples of SQL parsing](https://github.com/JSQLParser/JSqlParser/wiki/Examples-of-SQL-parsing)

- [SQL语言解析器的实现](https://wiki.postgresql.org/images/b/ba/SQL%E8%AF%AD%E8%A8%80%E8%A7%A3%E6%9E%90%E5%99%A8%E7%9A%84%E5%AE%9E%E7%8E%B0.pdf)

- [Parser 解析重写 SQL](https://blog.victorchu.info/posts/c3d08049/)

- [openGauss内核分析（三)：SQL解析](https://juejin.cn/post/7163657528520212511)
### 8.1 Syntax Check
- [SQL Syntax Checker Tools](https://www.sqlshack.com/sql-syntax-checker-tools/)
  

### 8.2 Semantic Check
- Paper : [Semantic Parsing with Syntax- and Table-Aware SQL Generation](https://aclanthology.org/P18-1034.pdf)

- [Awesome Sequence to SQL and Semantic Parsing](https://medium.com/@tao.yu/awesome-sequence-to-sql-and-semantic-parsing-1d7656861679)

### 8.3 Shared Pool Check
- [Shared Pool Management](http://pafumi.net/Shared_Pool_Management.html)
- Blog : [Oracle Identifying Shared Pool Contention](https://blog.toadworld.com/identifying_shared_pool_contention)

- [12.2 DBMS_SHARED_POOL: Pinning Objects](https://docstore.mik.ua/orelly/oracle/bipack/ch12_02.htm)

### 8.4 Actions
- [Surveying SQL parser libraries in a few high-level languages](https://datastation.multiprocess.io/blog/2022-04-11-sql-parsers.html)

- [SQL解析在美团的应用](https://tech.meituan.com/2018/05/20/sql-parser-used-in-mtdp.html)

- [TiDB 源码阅读系列文章（五）TiDB SQL Parser 的实现](https://cn.pingcap.com/blog/tidb-source-code-reading-5)

- [MYSQL · 新特性 · MySQL 8.0对Parser所做的改进](http://mysql.taobao.org/monthly/2017/04/02/)

- [MySQL · 源码分析 · 词法分析及其性能优化](http://mysql.taobao.org/monthly/2017/02/04/)

## 9. SQL Executor
- [SQL Executor, How does it work?](http://docs.safe.com/fme/html/FME_Desktop_Documentation/FME_Transformers/Transformers/sqlexecutor.htm?Highlight=sql%20delimiter)

- [MySQL · 内核特性 · 8.0 新的火山模型执行器](http://mysql.taobao.org/monthly/2020/07/01/)

## 9. SQL Optimization
- [15 Best Practices for SQL Optimization](https://betterprogramming.pub/15-best-practices-for-sql-optimization-956759626321)

- [Tips for SQL Database Optimization](https://www.alibabacloud.com/blog/tips-for-sql-database-optimization_595053)

- [Design and Practice of Self-Developed SQL Parser](https://www.alibabacloud.com/blog/design-and-practice-of-self-developed-sql-parser_598414)

- Paper : [A Pilot Study of Text-to-SQL Semantic Parsing for Vietnamese](https://openreview.net/pdf?id=uoUxTHRKEhi)

### 9.1 SQL Query Optimization
- [Top 10 SQL Query Optimization Tips to Improve Database Performance](https://www.mantralabsglobal.com/blog/sql-query-optimization-tips/), by Avishek Singh
  
- [SQL Query Optimization: How to Tune Performance of SQL Queries](https://blog.devart.com/how-to-optimize-sql-query.html)

- Oracle docs : [5 Query Optimization](https://docs.oracle.com/cd/E18283_01/timesten.112/e14261/query.htm)

- [The SQLite Query Optimizer Overview](https://www.sqlite.org/optoverview.html)

- [How to Optimize SQL Queries: Helpful Tips and Techniques
](https://www.apriorit.com/dev-blog/381-sql-query-optimization)

- [基于代价的慢查询优化建议](https://tech.meituan.com/2022/04/21/slow-query-optimized-advice-driven-by-cost-model.html)


### 9.2 Indexes Optimization
- Google Cloud docs : [Optimizing Indexes](https://cloud.google.com/datastore/docs/concepts/optimize-indexes)

- [How to use Indexing for SQL Query Optimization](https://towardsdatascience.com/indexing-for-sql-query-optimization-139b57db9fc6)

- [Database Optimization Techniques #1: Indexing](https://optimizdba.com/database-optimization-techniques-1-indexing/)

- [Understanding The Techniques Of Database Indexing](https://optimizdba.com/understanding-the-techniques-of-database-indexing/)

- [Optimizing SQL Server index strategies](https://www.sqlshack.com/optimizing-sql-server-index-strategies/)

- [Indexes - Optimize Queries](https://sqlmodel.tiangolo.com/tutorial/indexes/)

- [Examples: Using Indexes for Query Optimization](https://docs.oracle.com/en/database/other-databases/nosql-database/22.1/sqlreferencefornosql/examples-query-optimization.html)

- [Optimize index maintenance to improve query performance and reduce resource consumption](https://learn.microsoft.com/en-us/sql/relational-databases/indexes/reorganize-and-rebuild-indexes?view=sql-server-ver16)

- [How to create and optimize SQL Server indexes for better performance](https://solutioncenter.apexsql.com/how-to-create-and-optimize-sql-server-indexes-for-better-performance/)

- [Tutorial on MySQL Database Optimization using Indexes](https://www.section.io/engineering-education/mysql-query-optimization-using-indexes-with-examples/)

- [MySQL索引原理及慢查询优化](https://tech.meituan.com/2014/06/30/mysql-index.html)

- [SQL优化 · 经典案例 · 索引篇](http://mysql.taobao.org/monthly/2017/02/05/)
### 9.3 Table Optimization

- [How To Optimize MySQL Tables](https://phoenixnap.com/kb/mysql-optimize-table)
- [MySQL Optimize Table: How to Keep Your Database Running Smoothly](https://www.singlestore.com/blog/mysql-optimize-table/)

- MySQL docs : [8.5 Optimizing for InnoDB Table](https://dev.mysql.com/doc/refman/8.0/en/optimizing-innodb.html)

### 9.4 Buffer Cache Optimization
- [Buffer cache: What is it and how does it impact database performance?](https://blog.quest.com/buffer-cache-what-is-it-and-how-does-it-impact-database-performance/)

- [EXPLAIN (ANALYZE) needs BUFFERS to improve the Postgres query optimization process](https://postgres.ai/blog/20220106-explain-analyze-needs-buffers-to-improve-the-postgres-query-optimization-process)

### 9.5 Storage Optimization
- [Introduction to Memory-Optimized Tables](https://learn.microsoft.com/en-us/sql/relational-databases/in-memory-oltp/introduction-to-memory-optimized-tables?view=sql-server-ver16)

- [Best Practices for MySQL Database Storage Optimization](https://alibaba-cloud.medium.com/best-practices-for-mysql-database-storage-optimization-bb7d7166252e)

- AWS Storage Blog : [Storage for I/O-intensive SQL Server using Amazon EBS io2 Block Express](https://aws.amazon.com/blogs/storage/storage-for-i-o-intensive-sql-server-using-amazon-ebs-io2-block-express/)

- [Data Storage and Optimization](https://docs.stardog.com/operating-stardog/database-administration/storage-optimize)


### 9.7 table Structure Optimization

#### 9.7.1 data reduction 
- MySQL docs : [15.9.1.5 How Compression Works for InnoDB Tables](https://dev.mysql.com/doc/refman/8.0/en/innodb-compression-internals.html#:~:text=MySQL%20implements%20compression%20with%20the,in%20reduction%20of%20data%20size.)



#### 9.7.2 data  partition
- [When and how to use the SQL PARTITION BY clause](https://blog.quest.com/when-and-how-to-use-the-sql-partition-by-clause/)

- [SQL Database, Table and Data Partitioning: When and How to Do It](https://www.rudderstack.com/guides/sql-table-and-data-partitioning-how-to/)


### 9.8 Optimizer
Reference : https://zhuanlan.zhihu.com/p/363997416 , thanks henry liang

- Paper : [Orca: A Modular Query Optimizer Architecture for Big Data](https://15721.courses.cs.cmu.edu/spring2017/papers/15-optimizer2/p337-soliman.pdf) ,  SIGMOD 2014

- Paper : [An Overview of Cost-based Optimization of Queries with Aggregates](http://sites.computer.org/debull/95SEP-CD.pdf)

- Paper : [Optimizer plan change management: improved stability and performance in Oracle 11g](http://www.vldb.org/pvldb/vol1/1454175.pdf) , VLDB

- Paper : [Optimizing Queries over Partitioned Tables in MPP Systems](https://www.slideshare.net/emcacademics/optimizing-queriesoverpartitionedtablesinmpp-systems-1) , SIGMOD

- Paper : [Optimization of Common Table Expressions in MPP
Database Systems](http://www.vldb.org/pvldb/vol8/p1704-elhelw.pdf) , VLDB

### 9.9 SQL调优博客List
- [SQL调优实战总结](https://juejin.cn/post/6931596460119031821)

- [OceanBase SQL 调试优指南](https://www.oceanbase.com/docs/enterprise-oceanbase-database-cn-10000000000371594) , Alibaba Ant Group

- [PolarDB-X SQL 调优指南](https://doc.polardbx.com/sql-tunning/topics/) , Alibaba Cloud

- [TiDB SQL性能调优](https://docs.pingcap.com/zh/tidb/dev/sql-tuning-overview) , PingCAP

- [SQL调优常用方法](https://www.cnblogs.com/cnjavahome/p/4230534.html)

- [MySQL 性能调优](https://heapdump.cn/monographic/detail/45/4827112)

- [了解数据库性能优化](https://heapdump.cn/monographic/detail/18/4106442) ， thanks to TiDB

- [浅谈 数据库应用与 SQL 调优的原理](https://youwu.today/skill/thinkinsql/sql-performance/)

- [一文搞定MySQL性能调优](https://juejin.cn/post/6844904114250334215)

- [TiDB SQL调优实战——索引问题](https://tidb.net/blog/29aa8e6b)

- [MySQL 调优笔记](https://github.com/wardseptember/notes/blob/master/docs/Mysql/mysql%E8%B0%83%E4%BC%98%E7%AC%94%E8%AE%B0.md) ， Github Blogger : wardseptember

- [10 essential MySQL performance tuning tips](https://www.infoworld.com/article/3210905/10-essential-mysql-performance-tuning-tips.html)

- [101 MySQL tuning and optimization tips](https://topic.alibabacloud.com/a/101-mysql-tuning-and-optimization-tips_1_41_30053960.html) , Alibaba Cloud

## 10. Transaction management
- Google Cloud docs : [Transactions](https://cloud.google.com/datastore/docs/concepts/transactions)

- Paper 2006, [Cost-based query transformation in Oracle](https://dl.acm.org/doi/10.5555/1182635.1164215), VLDB

- [分布式事务，理论与实践](https://zhuanlan.zhihu.com/p/573680047)

- [MySQL · 引擎特性 · InnoDB 事务系统](http://mysql.taobao.org/monthly/2017/12/01/)

- [MySQL · 引擎特性 · InnoDB 事务子系统介绍](http://mysql.taobao.org/monthly/2015/12/01/)

- [Database · 原理介绍 · 数据库的事务与复制](http://mysql.taobao.org/monthly/2018/12/01/)

- [MongoDB · 引擎特性 · 事务实现解析](http://mysql.taobao.org/monthly/2018/07/03/)

- [Innodb中的事务隔离级别和锁的关系](https://tech.meituan.com/2014/08/20/innodb-lock.html)

- [Database · 理论基础 · 数据库事务隔离发展历史](http://mysql.taobao.org/monthly/2018/10/06/)
- [Database · 原理介绍 · Google Percolator 分布式事务实现原理解读](http://mysql.taobao.org/monthly/2018/11/02/)

- [第 12 章 事务和并发](https://docs.jboss.org/hibernate/orm/3.5/reference/zh-CN/html/transactions.html)

- Blog : [使用数据库事务](https://loopback.io/doc/zh/lb2/8880487.html)

- Blog : [11. 数据库事务](https://www.bmabk.com/index.php/post/33975.html)

- [InnoDB 事务分析-MVCC](https://leviathan.vip/2019/03/20/InnoDB%E7%9A%84%E4%BA%8B%E5%8A%A1%E5%88%86%E6%9E%90-MVCC/)

- [InnoDB 事务分析-Undo Log](https://leviathan.vip/2019/02/14/InnoDB%E7%9A%84%E4%BA%8B%E5%8A%A1%E5%88%86%E6%9E%90-Undo-Log/)
## Lock manager
- [MySQL · 引擎特性 · 8.0 Lock Manager](http://mysql.taobao.org/monthly/2020/04/09/)

- [MySQL · 引擎分析 · InnoDB行锁分析](https://zhuanlan.zhihu.com/p/56519305)

- [MySQL · 引擎特性 · InnoDB index lock前世今生](http://mysql.taobao.org/monthly/2015/07/05/)

- [MySQL · 最佳实践 · How to read the lock information from debugger](http://mysql.taobao.org/monthly/2020/10/03/)

- [PostgreSQL · 内核特性 · 死锁检测与解决](http://mysql.taobao.org/monthly/2021/07/03/)
- [MySQL · 引擎特性 · InnoDB 事务锁系统简介](http://mysql.taobao.org/monthly/2016/01/01/)

- [MySQL · 引擎特性 · Innodb 锁子系统浅析](http://mysql.taobao.org/monthly/2017/12/02/)

- [MySQL · 答疑解惑 · MySQL 锁问题最佳实践](http://mysql.taobao.org/monthly/2016/03/10/)

- [MySQL · 源码分析 · InnoDB读写锁实现分析](http://mysql.taobao.org/monthly/2020/04/02/)

- [InnoDB 事务 sharded 锁系统优化](https://leviathan.vip/2020/12/22/mysql-understand-trx-lock/)

- [MySQL · myrocks · 事务锁分析](http://mysql.taobao.org/monthly/2018/03/07/)

- [MySQL · 源码分析 · 事务锁调度分析](http://mysql.taobao.org/monthly/2021/09/01/)

- [MySQL · 引擎分析 · InnoDB行锁分析](http://mysql.taobao.org/monthly/2018/05/04/)

- [DataBase · 理论基础 · B+树数据库加锁历史](http://mysql.taobao.org/monthly/2022/01/01/)



## 11. Network
- [MySQL · 源码分析 · 网络通信模块浅析](http://mysql.taobao.org/monthly/2016/07/04/)

- [MySQL · 引擎特性 · 网络模块优化](http://mysql.taobao.org/monthly/2019/09/03/)

- [MongoDB · 特性分析 · 网络性能优化](http://mysql.taobao.org/monthly/2017/01/04/)


## 12. Serialization
- [可序列化的初学者指南](https://juejin.cn/post/7126776645414813710)

- AWS Redshift Blog : [可序列化的隔离](https://docs.aws.amazon.com/zh_cn/redshift/latest/dg/c_serial_isolation.html)

- [从SPI机制学习数据库驱动加载过程到SnakeYaml反序列化分析](https://moonsec.top/articles/123)

- [MySQL · 源码分析 · Tokudb序列化和反序列化过程](http://mysql.taobao.org/monthly/2017/06/01/)

- 美团技术团队博客 : [序列化和反序列化](https://tech.meituan.com/2015/02/26/serialization-vs-deserialization.htm)

## 13. Concurrency Control
- [MySQL · 引擎特性 · B+树并发控制机制的前世今生](http://mysql.taobao.org/monthly/2018/09/01/)

- [浅析数据库并发控制机制](http://catkang.github.io/2018/09/19/concurrency-control.html)

- [Database · 理论基础 · B-tree 物理结构的并发控制](http://mysql.taobao.org/monthly/2020/11/02/)

- [PolarDB · 引擎特性 · B-tree 并发控制优化](http://mysql.taobao.org/monthly/2021/12/04/)

- [MySQL · 最佳实践 · RDS MySQL 8.0 语句级并发控制](http://mysql.taobao.org/monthly/2019/06/02/)

- [PgSQL· 引擎特性 · 多版本并发控制介绍及实例分析](http://mysql.taobao.org/monthly/2019/08/01/)

- [数据库系统 · 事务并发控制 · Two-phase Lock Protocol](http://mysql.taobao.org/monthly/2021/10/02/)

- [How does MVCC (Multi-Version Concurrency Control) work](https://vladmihalcea.com/how-does-mvcc-multi-version-concurrency-control-work/)
## 14. Crash Recovery management
- [MySQL · 引擎特性 · InnoDB 崩溃恢复过程](http://mysql.taobao.org/monthly/2015/06/01/)

- [PgSQL · 特性分析 · checkpoint机制浅析](http://mysql.taobao.org/monthly/2017/04/04/)

- [PgSQL · 特性分析 · 数据库崩溃恢复（上）](http://mysql.taobao.org/monthly/2017/05/03/)

- [PgSQL · 特性分析 · 数据库崩溃恢复（下）](http://mysql.taobao.org/monthly/2017/06/04/)

- [MySQL · TokuDB · 日志子系统和崩溃恢复过程](http://mysql.taobao.org/monthly/2016/05/07/)

- [MySQL · myrocks · myrocks之备份恢复](http://mysql.taobao.org/monthly/2017/02/02/)

- [POLARDB · 理论基础 · 数据库故障恢复机制的前世今生](http://mysql.taobao.org/monthly/2019/01/01/)

- [POLARDB · 引擎特性 · PolarDB备份与恢复介绍](http://mysql.taobao.org/monthly/2022/07/02/)

- [B+树数据库故障恢复概述](http://mysql.taobao.org/monthly/2022/10/04/)

- [MySQL · 5.7改进 · Recovery改进](http://mysql.taobao.org/monthly/2014/11/03/)

- [MySQL · 源码分析 · binlog crash recovery](http://mysql.taobao.org/monthly/2018/07/05/)

## 15. NoSQL
- [NoSQL Tutorial: What is, Types of NoSQL Databases & Example](https://www.guru99.com/nosql-tutorial.html)

## 16. NewSQL
- [Database · 发展前沿 · NewSQL数据库概述](http://mysql.taobao.org/monthly/2020/12/01/)
- [我们是怎样打造一款分布式数据库的？](https://shardingsphere.apache.org/blog/cn/material/database/)
- [如何编写一个分布式数据库？](https://toutiao.io/posts/yedrf/preview) , PingCAP CEO刘奇
- [Understand the Differences Between NewSQL and Distributed SQL](https://www.yugabyte.com/blog/newsql-distributed-sql-differences/)


## 17. Distributed & Paralleled
- [Experiences with a Distributed, Scalable,
Methodological File System: AnalogicFS](http://nil.csail.mit.edu/6.824/2015/papers/katabi-analogicfs.pdf)

- [Monarch: Google’s Planet-Scale In-Memory
Time Series Database](http://www.vldb.org/pvldb/vol13/p3181-adams.pdf)

- Paper 2012 : [Spanner: Google's Globally-Distributed Database](https://www.usenix.org/system/files/conference/osdi12/osdi12-final-16.pdf) , OSDI


## 15. OLAP、OLTP、HTAP

### 15.1 OLAP
- WikiPedia : [OnLine Analytical Processing](https://en.wikipedia.org/wiki/Online_analytical_processing)

- AWS Blog : [What Is Online Analytical Processing?](https://aws.amazon.com/what-is/olap/)

- Azure Blog : [Online analytical processing (OLAP)](https://learn.microsoft.com/en-us/azure/architecture/data-guide/relational-data/online-analytical-processing)

- [An Overview of Data Warehousing and OLAP Technology](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/sigrecord.pdf)

### 15.2 OLTP
- wikiPedia : [Online transaction processing](https://en.wikipedia.org/wiki/Online_transaction_processing)

- [What is OLTP? Definition, Architecture, Example](https://www.guru99.com/what-is-oltp.html)

- Azure Blog : [Online transaction processing (OLTP)](https://learn.microsoft.com/en-us/azure/architecture/data-guide/relational-data/online-transaction-processing)

- [LAP vs. OLTP: Understanding 13 Crucial Differences](https://www.spiceworks.com/tech/artificial-intelligence/articles/olap-vs-oltp/)


### 15.3 HTAP
- [Hybrid transactional/analytical processing](https://en.wikipedia.org/wiki/Hybrid_transactional/analytical_processing)

- Tsinghua University databaseGroup Sigmod2022 slide : [HTAP database : A Tutorial](https://dbgroup.cs.tsinghua.edu.cn/ligl/papers/sigmod22-htap-slides.pdf)

- [What is HTAP?](https://www.singlestore.com/blog/what-is-htap/)

- [A Common Database Approach for OLTP and OLAP Using an In-Memory Column DataBase](http://www.sigmod09.org/images/sigmod1ktp-plattner.pdf)

- PingCAP : [How We Build an HTAP Database That Simplifies Your Data Platform](https://www.pingcap.com/blog/how-we-build-an-htap-database-that-simplifies-your-data-platform/)

- StoneDB 文章
  - [什么是真正的HTAP？（一）背景篇](https://zhuanlan.zhihu.com/p/542008685)
  - [什么是真正的 HTAP ？（二）挑战篇](https://zhuanlan.zhihu.com/p/544938116)

- AlibabaCloud Community Blog : : [400x Faster HTAP Real-time Data Analysis with PolarDB](https://www.alibabacloud.com/blog/400x-faster-htap-real-time-data-analysis-with-polardb_598985)

- GreenPlum database Blog : [World Class Open Source Distributed HTAP Database Based On PostgreSQL](https://greenplum.org/world-class-open-source-distributed-htap-database-based-on-postgresql/)

- Paper 2020 : [TiDB: A Raft-based HTAP Database](https://www.vldb.org/pvldb/vol13/p3072-huang.pdf), VLDB

- [PolarDB for PostgreSQL HTAP 架构详解](https://apsaradb.github.io/PolarDB-for-PostgreSQL/zh/theory/arch-htap.html)

- Paper 2022 : [Kernel-Assisted Copy-on-Write Snapshots for Main-Memory HTAP
Databases](https://www.lfdr.de/Publications/2022/master_thesis_wolf.pdf)

- [DataBase · 引擎特性 · OLAP/HTAP列式存储引擎概述](http://mysql.taobao.org/monthly/2021/03/05/)

- [DataBase · 理论基础 · HTAP列存引擎探秘](http://mysql.taobao.org/monthly/2022/02/02/)

- [PolarDB MySQL·HTAP·浅析IMCI的列存数据压缩](http://mysql.taobao.org/monthly/2022/08/01/)

- [MySQL · HTAP · 分析型执行引擎](http://mysql.taobao.org/monthly/2021/04/04/)

- [HybridDB · 最佳实践 · OLAP和OLTP一体化打造](http://mysql.taobao.org/monthly/2016/12/05/)

- [MySQL · HTAP · 分析型执行引擎](http://mysql.taobao.org/monthly/2021/04/04/)
## 16. Graph Database
### 16.1 Courses
- YouTube Video : [Introduction to Graph Databases Series](https://www.youtube.com/watch?v=REVkXVxvMQE&list=PL9Hl4pk2FsvWM9GWaguRhlCQ-pa-ERd4U&index=1)

### 16.2 Books
- [Graph Database : New Oppotunities For Connected Data](https://web4.ensiie.fr/~stefania.dumbrava/OReilly_Graph_Databases.pdf) , Ian Robinson, Jim Webber & Emil Eifrem

- [Graph Databases For Beginners](https://neo4j.com/wp-content/themes/neo4jweb/assets/images/Graph_Databases_for_Beginners.pdf) , Merkl Sasaki, Joy Chao & Rachel Howard

- [Graph-Databases-For-Dummies](https://joshbersin.com/wp-content/uploads/2022/02/Graph-Databases-For-Dummies.pdf) ,  Dr. Jim Webber & Rik Van Bruggen

- [The Definitive Guide to Graph Databases for the RDBMS Developer](https://go.neo4j.com/rs/710-RRC-335/images/Definitive-Guide-Graph-Databases-for-RDBMS-Developer.pdf) , Michael Hunger, Ryan Boyd & William Lyon

### 16.3 Papers
- Paper 2022 : [ByteGraph: A High-Performance Distributed Graph  Database in ByteDance](https://vldb.org/pvldb/vol15/p3306-li.pdf) , VLDB


### 16.4 Blogs
- [ByteGraph: A Graph Database for TikTok](https://www.mydistributed.systems/2023/01/bytegraph-graph-database-for-tiktok.html)

- [字节跳动自研万亿级图数据库 & 图计算实践](https://zhuanlan.zhihu.com/p/109401046)

- 美团技术团队 Blog : [美团图数据库平台建设及业务实践](https://tech.meituan.com/2021/04/01/nebula-graph-practice-in-meituan.html)

- [Graph Databases for Beginners: Why Graph Technology Is the Future](https://neo4j.com/blog/why-graph-databases-are-the-future/)

- [Graph Databases: How They Work, When to Use Them & the Advantages They Offer](https://www.influxdata.com/graph-database/)

- [Developing a Small-Scale Graph Database: A Ten Step Learning Guide for Beginners](https://jitp.commons.gc.cuny.edu/developing-a-small-scale-graph-database-a-ten-step-learning-guide-for-beginners/)

- [Graph Database Tutorial With Neo4j](https://www.cl.cam.ac.uk/teaching/1920/Databases/graph-tutorial.html)

- [Getting started with Graph database using Neo4j](https://dev.to/codemaker2015/getting-started-with-graph-database-using-neo4j-38im)

- 白皮书 : [图数据库技术十大案例](https://go.neo4j.com/rs/710-RRC-335/images/Neo4j-Top-Use-Cases-ZH.pdf)

## 16. Project Source Code Analysis
Just collect, some databases have not been read yet. Thanks to all Authors.

|Database|DataBase Type|Blog|Github|
|--|--|--|--|
|SQLite|a small relational database management system|[SQLite源码分析](https://huili.github.io/index.html)|https://github.com/sqlite/sqlite|
|LevelDB|fast key-value storage library|[LevelDB 源码剖析](https://www.zhihu.com/column/c_1282795241104465920)|https://github.com/google/leveldb|
|MySQL|||
|PostGreSQL||[PostGreSQL源码解读系列](https://www.cnblogs.com/flying-tiger/category/881004.html?page=3)||
|Redis|in-memory database that persists on disk.|[1. 如何阅读 Redis 源码？](https://blog.huangz.me/diary/2014/how-to-read-redis-source-code.html)<br>[2. redis源码解析](https://redissrc.readthedocs.io/en/latest/index.html)|https://github.com/redis/redis|
|MongoDB|Cloud-Native Document Database|[MongoDB 内核源码分析](https://github.com/y123456yz/reading-and-annotate-mongodb-3.6) |https://github.com/mongodb/mongo|
|TiDB|cloud-native, distributed, MySQL-Compatible database|[TiDB源码阅读分析](https://cn.pingcap.com/blog/?tag=TiDB%20%E6%BA%90%E7%A0%81%E9%98%85%E8%AF%BB)|https://github.com/pingcap/tidb|
|TiKV|distributed key-value database|[TiKV源码解析系列](https://cn.pingcap.com/blog/?tag=TiKV%20%E6%BA%90%E7%A0%81%E8%A7%A3%E6%9E%90)||
|PolarDB-X|cloud native distributed SQL Database|[PolarDB-X 源码解读](https://www.zhihu.com/column/c_1449680469579640832)|https://github.com/polardb/polardbx-sql|
|OceanBase|distributed relational database ||https://github.com/oceanbase/oceanbase|
|openGauss|open source relational database management system|[openGauss数据库源码解析](https://www.zhihu.com/column/c_1358363246349635584)|https://github.com/opengauss-mirror|
|StoneDB|A Real-time HTAP Database|[StoneDB 源码解读系列](https://www.zhihu.com/column/c_1578402452771938304)|
|RocksDB|A Persistent Key-Value Store for Flash and RAM Storage|[官方wiki文档](https://github.com/facebook/rocksdb/wiki)|https://github.com/facebook/rocksdb|
|ToplingDB|RocksDB的增强分支|N/A|https://github.com/topling/toplingdb|
|Greenplum|open-source massively parallel data platform for analytics, machine learning and AI.|[Greenplum 分布式数据库内核揭秘(上篇)](https://cn.greenplum.org/greenplum-distributed-database-kernel-1/)<br>[Greenplum 分布式数据库内核揭秘(下篇)](https://cn.greenplum.org/greenplum-distributed-database-kernel-2/)|https://github.com/greenplum-db/gpdb|
|YugabyteDB|high-performance, cloud-native, distributed SQL database that aims to support all PostgreSQL features.|待更新|https://github.com/yugabyte/yugabyte-db|
|Neo4j|Graph Database|待更新|https://github.com/neo4j/neo4j|
|JanusGraph|open-source, distributed graph database|待更新|https://github.com/JanusGraph/janusgraph|
|OpenMLDB|an open-source machine learning database|待更新|https://github.com/4paradigm/OpenMLDB|

taobao MySQL 数据库内核月报 ：http://mysql.taobao.org/monthly/

## 17. Mini-Project Labs
- DeepDB : https://github.com/deepbodra97/Database-System-Implementation
- Mini-OB : https://open.oceanbase.com/activities/4921877

- CS 15-445 Labs

## 18. AI4DB and DB4AI (frontier tech)
- University of Magdeburg slides:
  - slide 01 : https://www.dbse.ovgu.de/en/-p-578-EGOTEC-35lsmf8qh52t9v3rhrjdojrd46/_/5_ai-1.pdf
  - slide 02 : https://www.dbse.ovgu.de/-p-578/_/5_ai-2.pdf
- Tsinghua University databaseGroup Github : https://github.com/TsinghuaDatabaseGroup/AIDB
- Tsinghua & MIT Paper : [AI Meets Database: AI4DB and DB4AI](https://dbgroup.cs.tsinghua.edu.cn/ligl/papers/sigmod21-tutorial-paper.pdf) , SIGMOD2021
- openGauss Blog : [openGauss AI4DB and DB4AI](https://blog.opengauss.org/en/post/2022/opengauss-ai4db-and-db4ai/)
- MIT databaseGroup : http://dsg.csail.mit.edu/mlforsystems/papers/
- Blogger Github : https://github.com/LumingSun/ML4DB-paper-list


## Database Retrospective
- [Databases in 2021: A Year in Review](https://ottertune.com/blog/2021-databases-retrospective/) , Andy Pavlo
- [Databases in 2022: A Year in Review](https://ottertune.com/blog/2022-databases-retrospective/) , Andy Pavlo