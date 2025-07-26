## Storage

- [ ] 📄 [The Adaptive Radix Tree: ARTful Indexing for Main-Memory Databases](https://db.in.tum.de/~leis/papers/ART.pdf) (V Leis, A Kemper, T Neumann 2013)
- [ ] 📄 [Aries: A Transaction Recovery Method Supporting Fine-Granularity Locking and Partial Rollbacks Using Write-Ahead Logging](https://cs.stanford.edu/people/chrismre/cs345/rl/aries.pdf) (C Mohan et al 1992)
- [ ] 📄 [bLSM: A General Purpose Log Structured Merge Tree](http://www.eecs.harvard.edu/~margo/cs165/papers/gp-lsm.pdf) (R Sears, R Ramakrishnan 2012)
- [ ] 📄 [Building a Bw-Tree Takes More Than Just Buzz Words](http://www.cs.cmu.edu/~huanche1/publications/open_bwtree.pdf) (Z Wang et al 2018)
- [ ] 📄 [Constant Time Recovery in Azure SQL Database](https://www.microsoft.com/en-us/research/uploads/prod/2019/06/p700-antonopoulos.pdf) (P Antonopoulos et al 2019)
- [ ] 📄 [Enabling Efficient OS Paging for Main-Memory OLTP Databases](https://15721.courses.cs.cmu.edu/spring2016/papers/a7-stoica.pdf) (R Stoica, A Ailamaki 2013)
- [ ] 📄 [Jungle: Towards Dynamically Adjustable Key-Value Store by Combining LSM-Tree and Copy-On-Write B+-Tree](https://greensky00.github.io/pdf/jungle_hotstorage19.pdf) (JS Ahn et al 2019)
- [ ] 📄 [Larger-than-Memory Data Management on Modern Storage Hardware for In-Memory OLTP Database Systems](https://www.cc.gatech.edu/~jarulraj/papers/2016.caching.damon.pdf) (L Ma et al 2016)
- [ ] 📄 [The Bw-Tree: A B-tree for New Hardware Platforms](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/bw-tree-icde2013-final.pdf) (JJ Levandoski, DB Lomet, S Sengupta 2013)
- [ ] 📄 [The Log-Structured Merge Tree](https://www.cs.umb.edu/~poneil/lsmtree.pdf) (P O'Neil, E Cheng, D Gawklik, E O'Neil 1996)
- [ ] 📄 [The Ubiquitous B-Tree](http://cgi.di.uoa.gr/~ad/M149/ubiquitous_btree.pdf) (D Comer 1979)
- [ ] 📄 [WiscKey: Separating Keys from Values in SSD-Conscious Storage](https://www.usenix.org/system/files/conference/fast16/fast16-papers-lu.pdf) (L Lu, TS Pillai, AC Arpaci-Dusseau, RH Arpaci-Dusseau 2016)

## Storage

### NoSQL Systems

Papers:

- 2006, [Bigtable: A Distributed Storage System for Structured Data](https://static.googleusercontent.com/media/research.google.com/en//archive/bigtable-osdi06.pdf), OSDI
- 2007, [Dynamo: Amazon’s Highly Available Key-value Store](https://sites.cs.ucsb.edu/~agrawal/fall2009/dynamo.pdf), SOSP
- 2008, [PNUTS: Yahoo!’s Hosted Data Serving Platform](https://sites.cs.ucsb.edu/~agrawal/fall2009/PNUTS.pdf), VLDB
- 2010, [Cassandra - A Decentralized Structured Storage System](https://www.cs.cornell.edu/projects/ladis2009/papers/lakshman-ladis2009.pdf), SOSP
- 2019, [PNUTS to Sherpa: Lessons from Yahoo!’s Cloud Database ](http://www.vldb.org/pvldb/vol12/p2300-cooper.pdf), VLDB

### Buffer Management

Courses:

- CMU [Database Systems (15-445/645)](https://15445.courses.cs.cmu.edu/fall2019/schedule.html), thanks to [Andy Pavlo](http://www.cs.cmu.edu/~pavlo/)
    - [Buffer Pools](https://15445.courses.cs.cmu.edu/fall2019/schedule.html#sep-11-2019)

Papers:

- 1987, [The 5 Minute Rule for Trading Memory for Disc Accesses and the 5 Byte Rule for Trading Memory for CPU Time](https://www.hpl.hp.com/techreports/tandem/TR-86.1.pdf), SIGMOD
- 2008, [The Five Minute Rule 20 Years Later and How Flash Memory Changes the Rules](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.227.3846&rep=rep1&type=pdf), ACM Queue
- 2018, [Managing Non-Volatile Memory in Database Systems](https://db.in.tum.de/people/sites/vanrenen/papers/HyMem.pdf?lang=de), SIGMOD
- 2018, [LeanStore: In-Memory Data Management Beyond Main Memory](https://db.in.tum.de/~leis/papers/leanstore.pdf), ICDE
- 2020, [Umbra: A Disk-Based System with In-Memory Performance](http://cidrdb.org/cidr2020/papers/p29-neumann-cidr20.pdf), CIDR

### Disk IO

Blogs:

- [On Disk IO, Part 1: Flavors of IO](https://medium.com/databasss/on-disk-io-part-1-flavours-of-io-8e1ace1de017), thanks to [Alex](https://twitter.com/ifesdjeen)
- [On Disk IO, Part 2: More Flavours of IO](https://medium.com/databasss/on-disk-io-part-2-more-flavours-of-io-c945db3edb13?), thanks to [Alex](https://twitter.com/ifesdjeen)
- [On Disk IO, Part 3: LSM Trees](https://medium.com/databasss/on-disk-io-part-3-lsm-trees-8b2da218496f), thanks to [Alex](https://twitter.com/ifesdjeen)
- [On Disk IO, Part 4: B-Trees and RUM Conjecture](https://medium.com/databasss/on-disk-storage-part-4-b-trees-30791060741), thanks to [Alex](https://twitter.com/ifesdjeen)
- [On Disk IO, Part 5: Access Patterns in LSM Trees](https://medium.com/databasss/on-disk-io-access-patterns-in-lsm-trees-2ba8dffc05f9), thanks to [Alex](https://twitter.com/ifesdjeen)
- [Ensuring data reaches disk(LWN)](https://lwn.net/Articles/457667/)
- [Read, write & space amplification - pick 2](http://smalldatum.blogspot.com/2015/11/read-write-space-amplification-pick-2_23.html), thanks to [Mark Callaghan](https://twitter.com/markcallaghandb)

Papers:

- 2016, [Design Tradeoffs of Data Access Methods](http://scholar.harvard.edu/files/stratos/files/rum-tutorial.pdf?m=1461167186), SIGMOD
- 2016, [Designing Access Methods: The RUM Conjecture](https://stratos.seas.harvard.edu/files/stratos/files/rum.pdf), EDBT

### B-Tree

Blogs:

- [B树、B+树索引算法原理（上）](https://www.codedump.info/post/20200609-btree-1/) thanks to [codedump](https://www.codedump.info/)
- [B树、B+树索引算法原理（下）](https://www.codedump.info/post/20200615-btree-2/)

Courses:

- CMU [Database Systems (15-445/645)](https://15445.courses.cs.cmu.edu/fall2019/schedule.html), thanks to [Andy Pavlo](http://www.cs.cmu.edu/~pavlo/)
    - [Trees Indexes I](https://15445.courses.cs.cmu.edu/fall2019/schedule.html#sep-18-2019)
    - [Trees Indexes II](https://15445.courses.cs.cmu.edu/fall2019/schedule.html#sep-23-2019)

- CMU [Advanced Database Systems (15-721)](https://15721.courses.cs.cmu.edu/spring2020/schedule.html), thanks to [Andy Pavlo](http://www.cs.cmu.edu/~pavlo/)
    - [OLTP Indexes (B+Tree Data Structures)](https://15721.courses.cs.cmu.edu/spring2020/schedule.html#feb-03-2020)

Papers:

- 1979, [The Ubiquitous B-Tree](http://carlosproal.com/ir/papers/p121-comer.pdf)

### LSM-Tree

Papers:

- 1996, [The Log-Structured Merge-Tree (LSM-Tree)](https://www.cs.umb.edu/~poneil/lsmtree.pdf),
- 2014, [A Comparison of Fractal Trees to Log-Structured Merge (LSM) Trees](http://www.pandademo.com/wp-content/uploads/2017/12/A-Comparison-of-Fractal-Trees-to-Log-Structured-Merge-LSM-Trees.pdf)
- 2017, [WiscKey: Separating Keys from Values in SSD-conscious Storage](https://www.usenix.org/system/files/conference/fast16/fast16-papers-lu.pdf), TOS
- 2019, [LSM-based Storage Techniques: A Survey](https://arxiv.org/pdf/1812.07527.pdf)

### Learned Indexes Structures

Papers:

- 2018, [The Case for Learned Index Structures](https://www.cl.cam.ac.uk/~ey204/teaching/ACS/R244_2018_2019/papers/Kraska_SIGMOD_2018.pdf)
- 2019, [Learning Multi-dimensional Indexes](https://arxiv.org/pdf/1912.01668.pdf)
- 2020, [XIndex: A Scalable Learned Index for Multicore Data Storage](https://dl.acm.org/doi/pdf/10.1145/3332466.3374547)
- 2020, [RadixSpline: A Single-Pass Learned Index](https://dl.acm.org/doi/10.1145/3401071.3401659), [Source Code](https://github.com/learnedsystems/RadixSpline), aiDM@SIGMOD
- 2020, [The PGM-index: a fully-dynamic compressed learned index with provable worst-case bounds](http://www.vldb.org/pvldb/vol13/p1162-ferragina.pdf), [Source Code](https://github.com/gvinciguerra/PGM-index), VLDB
- 2020, [From WiscKey to Bourbon: A Learned Index for Log-Structured Merge Trees](http://pages.cs.wisc.edu/~yifann/bourbon-osdi20.pdf)

