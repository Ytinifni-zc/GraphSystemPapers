# 图计算系统论文
## 每种计算模式的代表性文章
- 以点为中心 [Pregel (SIGMOD'10)](paper/Pregel.pdf) : MALEWICZ G, AUSTERN M H, BIK A J, et al. Pregel: a system for large-scale graph processing[C]//Proceedings of the 2010 ACM SIGMOD International Conference on Management of data. ACM, 2010: 135-146.
- 以边为中心 [X-Stream (SOSP'13)](paper/X-Stream.pdf) : ROY A, MIHAILOVIC I, ZWAENEPOEL W. X-stream: Edge-centric graph processing using streaming partitions[C]//Proceedings of the Twenty-Fourth ACM Symposium on Operating Systems Principles. ACM, 2013: 472-488.
- 点边混合计算 [Ligra (PPoPP'13)](paper/Ligra.pdf) : SHUN J, BLELLOCH G E. Ligra: a lightweight graph processing framework for shared memory[C]//ACM Sigplan Notices: volume 48. ACM, 2013: 135-146.
- 以子图为中心 [Arabesque (SOSP'15)](paper/Arabesque.pdf) : TEIXEIRA C H, FONSECA A J, SERAFINI M, et al. Arabesque: a system for distributed graph mining[C]//Proceedings of the 25th Symposium on Operating Systems Principles. ACM, 2015: 425-440.
  * 以子图为中心旨在解决图挖掘任务

## 分布式图计算系统代表性文章
- [PowerGraph (OSDI'12)](paper/PowerGraph.pdf) : GONZALEZ J E, LOW Y, GU H, et al. Powergraph: Distributed graph-parallel computation on natural graphs[C]//Presented as part of the 10th {USENIX} Symposium on Operating Systems Design and Implementation ({OSDI} 12). 2012: 17-30.
- [Gemini (OSDI'14)](paper/Gemini.pdf) :  ZHU X, CHEN W, ZHENG W, et al. Gemini: A computation-centric distributed graph processing system[C]//12th {USENIX} Symposium on Operating Systems Design and Implementation ({OSDI} 16). 2016: 301-316.

## 单机图计算系统代表性文章
- [GraphChi (OSDI'12)](paper/GraphChi.pdf) : KYROLA A, BLELLOCH G, GUESTRIN C. Graphchi: Large-scale graph computation on just a {PC}[C]//Presented as part of the 10th {USENIX} Symposium on Operating Systems Design and Implementation ({OSDI} 12). 2012: 31-46.
- [GridGraph (ATC'15)](paper/GridGraph.pdf) : ZHU X, HAN W, CHEN W. Gridgraph: Large-scale graph processing on a single machine using 2-level hierarchical partitioning[C]//2015 {USENIX} Annual Technical Conference ({USENIX}{ATC} 15). 2015: 375-386.
- [GraphMat (VLDB'15)](paper/GraphMat.pdf) : Sundaram N, Satish N, Patwary M M A, et al. GraphMat: High performance graph analytics made productive[J]. Proceedings of the VLDB Endowment, 2015, 8(11).

### 最近几年着重考虑SSD性能的单机图计算系统代表性文章
- [FlashGraph (FAST'15)](paper/FlashGraph.pdf) : Zheng D, Mhembere D, Burns R, et al. FlashGraph: Processing billion-node graphs on an array of commodity SSDs[C]//13th {USENIX} Conference on File and Storage Technologies ({FAST} 15). 2015: 45-58.
- [Graphene (FAST'17)](paper/Graphene.pdf) : Liu H, Huang H H. Graphene: Fine-grained {IO} management for graph computing[C]//15th {USENIX} Conference on File and Storage Technologies ({FAST} 17). 2017: 285-300.
- [Basc (ATC'19)](paper/Basc.pdf) : Lee E, Kim J, Lim K, et al. Pre-select static caching and neighborhood ordering for BFS-like algorithms on disk-based graph engines[C]//2019 {USENIX} Annual Technical Conference ({USENIX}{ATC} 19). 2019: 459-474.
  * 本文对图节点排序对计算性能的影响进行了讨论，其引用的另一篇专门对此进行讨论的文章为 [Gorder (SIGMOD'16)](paper/Gorder.pdf) : Wei H, Yu J X, Lu C, et al. Speedup graph processing by graph ordering[C]//Proceedings of the 2016 International Conference on Management of Data. 2016: 1813-1828.
- [LUMOS (ATC'19)](paper/Lumos.pdf) : Vora K. {LUMOS}: Dependency-Driven Disk-based Graph Processing[C]//2019 {USENIX} Annual Technical Conference ({USENIX}{ATC} 19). 2019: 429-442.

## 图挖掘系统代表性文章
除了上面提到的Arabesque，还有2篇最近发表的文章
- [RStream (OSDI'18)](paper/RStream.pdf) : Wang K, Zuo Z, Thorpe J, et al. Rstream: Marrying relational algebra with streaming for efficient graph mining on a single machine[C]//13th {USENIX} Symposium on Operating Systems Design and Implementation ({OSDI} 18). 2018: 763-782.
- [AutoMine (SOSP'19)](paper/AutoMine.pdf) : Mawhirter D, Wu B. AutoMine: harmonizing high-level abstraction and high performance for graph mining[C]//Proceedings of the 27th ACM Symposium on Operating Systems Principles. 2019: 509-523.
