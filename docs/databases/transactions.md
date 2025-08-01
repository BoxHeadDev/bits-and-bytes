## Transactions

- [ ] 📄 [**A Critique of ANSI SQL Isolation Levels**](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/tr-95-51.pdf) (H Berenson et al 1995)
- [ ] 🔗 [**Consistency Models**](https://jepsen.io/consistency) (Jepsen 2016)
- [ ] 📄 [**Generalized Isolation Level Definitions**](http://pmg.csail.mit.edu/papers/icde00.pdf) (A Adya, B Liskov, P ONeil 2000)
- [ ] 📖 [**Transaction Processing: Concepts and Techniques**](https://www.amazon.com/Transaction-Processing-Concepts-Techniques-Management/dp/1558601902#customerReviews) (J Gray, A Reuter 1992)
- [ ] 📄 [A Critique of Snapshot Isolation](https://dl.acm.org/doi/pdf/10.1145/2168836.2168853) (DG Ferro, M Yabandeh 2012)
- [ ] 📄 [ACIDRain: Concurrency-Related Attacks on Database-Backed Web Applications](http://www.bailis.org/papers/acidrain-sigmod2017.pdf) (P Bailis, T Warszawski 2017)
- [ ] 📄 [An Empirical Evaluation of In-Memory Multi-Version Concurrency Control](https://yingjunwu.github.io/papers/vldb2017.pdf) (Y Wu et al 2017)
- [ ] 📄 [Building Consistent Transactions with Inconsistent Replication](http://delivery.acm.org/10.1145/2820000/2815404/p263-zhang.pdf) (I Zhang et al 2015)
- [ ] 📄 [Calvin: Fast Distributed Transactions for Partitioned Database Systems](http://cs.yale.edu/homes/thomson/publications/calvin-sigmod12.pdf) (DJ Abadi et al 2012) _"The Calvin paper"_
- [ ] 📄 [Consistency in Non-Transactional Distributed Storage Systems](https://arxiv.org/pdf/1512.00168.pdf) (P Viotti, M Vukolić 2016)
- [ ] 📄 [Highly Available Transactions: Virtues and Limitations](http://www.vldb.org/pvldb/vol7/p181-bailis.pdf) (P Bailis, JM Hellerstein et al 2013)
- [ ] 📄 [Lazy State Determination: More concurrency for contending linearizable transactions](https://arxiv.org/pdf/2007.09733.pdf) (TM Vale et al 2020)
- [ ] 📄 [Naming and Synchronization in a Decentralized Computer System](https://dspace.mit.edu/bitstream/handle/1721.1/16279/05331643-MIT.pdf) (DP Reed 1978) _"The MVCC paper"_
- [ ] 📄 [Rethinking Serializable Multiversion Concurrency Control](http://www.jmfaleiro.com/pubs/multiversion-vldb2015.pdf) (JM Faleiro, DJ Abadi 2015)
- [ ] 📄 [Scalable Atomic Visibility with RAMP Transactions](http://www.bailis.org/papers/ramp-sigmod2014.pdf) (P Bailis et al 2014)
- [ ] 📄 [Serializable Isolation for Snapshot Databases](https://courses.cs.washington.edu/courses/cse444/08au/544M/READING-LIST/fekete-sigmod2008.pdf) (MJ Cahill, U Röhm, AD Fekete 2008)
- [ ] 💬 [What Does Write Skew Look Like](http://justinjaffray.com/what-does-write-skew-look-like/) (J Jaffray 2018)

## Transaction

### Isolation Levels

Blogs:

- [一致性模型](https://www.jianshu.com/p/3673e612cce2), thanks to [siddontang](https://www.jianshu.com/u/1yJ3ge)

Papers:

- 1995, [A Critique of ANSI SQL Isolation Levels](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/tr-95-51.pdf), SIGMOD
- 2000, [Generalized Isolation Level Definitions](http://pmg.csail.mit.edu/papers/icde00.pdf), Proceedings of 16th International Conference on Data Engineering

### Concurrency Control

Courses:

- CMU [Database Systems (15-445/645)](https://15445.courses.cs.cmu.edu/fall2019/schedule.html), thanks to [Andy Pavlo](http://www.cs.cmu.edu/~pavlo/)
    - [Concurrency Control Theory](https://15445.courses.cs.cmu.edu/fall2019/schedule.html#oct-23-2019)
    - [Two-Phase Locking Concurrency Control](https://15445.courses.cs.cmu.edu/fall2019/schedule.html#oct-28-2019)
    - [Timestamp Ordering Concurrency Control](https://15445.courses.cs.cmu.edu/fall2019/schedule.html#oct-30-2019)
    - [Multi-Version Concurrency Control](https://15445.courses.cs.cmu.edu/fall2019/schedule.html#nov-04-2019)

- CMU [Advanced Database Systems (15-721)](https://15721.courses.cs.cmu.edu/spring2020/schedule.html), thanks to [Andy Pavlo](http://www.cs.cmu.edu/~pavlo/)
    - [Multi-Version Concurrency Control (Design Decisions)](https://15721.courses.cs.cmu.edu/spring2020/schedule.html#jan-22-2020)
    - [Multi-Version Concurrency Control (Protocols)](https://15721.courses.cs.cmu.edu/spring2020/schedule.html#jan-27-2020)
    - [Multi-Version Concurrency Control (Garbage Collection)](https://15721.courses.cs.cmu.edu/spring2020/schedule.html#jan-29-2020)

Papers:

- 1976, [The Notions of Consistency and Predicate Locks in a Database System](http://jimgray.azurewebsites.net/papers/on%20the%20notions%20of%20consistency%20and%20predicate%20locks%20in%20a%20database%20system%20cacm.pdf), Communications of the ACM
- 1981, [Concurrency Control in Distributed Database Systems](https://people.eecs.berkeley.edu/~brewer/cs262/concurrency-distributed-databases.pdf), ACM Computing Surveys
- 1981, [On Optimistic Methods for Concurrency Control](https://www.eecs.harvard.edu/~htk/publication/1981-tods-kung-robinson.pdf), ACM Transactions on Database Systems
- 1983, [Multiversion Concurrency Control - Theory and Algorithms](https://sites.fas.harvard.edu/~cs265/papers/bernstein-1983.pdf), ACM Transactions on Database Systems
- 2012, [Serializable Snapshot Isolation in PostgreSQL](http://www.vldb.org/pvldb/vol4/p783-jung.pdf), VLDB
- 2012, [Calvin: Fast Distributed Transactions for Partitioned Database Systems](http://cs.yale.edu/homes/thomson/publications/calvin-sigmod12.pdf), SIGMOD
- 2014, [MaaT: effective and scalable coordination of distributed transactions in the cloud](http://www.nawab.me/Uploads/MaaT_VLDB2014.pdf), VLDB
- 2014, [Staring into the Abyss: An Evaluation of Concurrency Control with One Thousand Cores](http://www.vldb.org/pvldb/vol8/p209-yu.pdf), VLDB
- 2014, [An Evaluation of the Advantages and Disadvantages of Deterministic Database Systems](http://www.vldb.org/pvldb/vol7/p821-ren.pdf), VLDB
- 2015, [Fast Serializable Multi-Version Concurrency Control for Main-Memory Database Systems](https://db.in.tum.de/~muehlbau/papers/mvcc.pdf), SIGMOD
- 2017, [An Empirical Evaluation of In-Memory Multi-Version Concurrency Control](http://www.vldb.org/pvldb/vol10/p781-Wu.pdf), VLDB
- 2017, [An Evaluation of Distributed Concurrency Control](https://www.vldb.org/pvldb/vol10/p553-harding.pdf), VLDB
- 2019, [Scalable Garbage Collection for In-Memory MVCC Systems](https://db.in.tum.de/~boettcher/p128-boettcher.pdf), VLDB


Distributed Transactions:
Reading Materials
- Database Internals: 5. Transaction Processing and Recovery
- Database Internals: 13. Distributed Transactions

ACID
- https://en.wikipedia.org/wiki/ACID

Isolation (Optional)
- https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/tr-95-51.pdf
- https://www.jianshu.com/p/3673e612cce2 (Chinese)

Spanner (Optional)
- https://storage.googleapis.com/pub-tools-public-publication-data/pdf/45855.pdf
- https://www.jianshu.com/p/f307bd2023f5 (Chinese)

Percolator
- https://tikv.org/docs/deep-dive/distributed-transaction/percolator/
- https://tikv.org/docs/deep-dive/distributed-transaction/optimized-percolator/



