# shijielaw.data
Some datasets used in my projects.
(Here)[https://zhuanlan.zhihu.com/p/361715390] to find the datasets you need...


### 1. Datasets for Node Classification:
| No.  |   Data   |                             Link                             |                     Statistics                     |                             Note                             |
| :--: | :------: | :----------------------------------------------------------: | :------------------------------------------------: | :----------------------------------------------------------: |
|  1   |   Cora   |           [Cora](https://linqs.org/datasets/#cora)           | Nodes=2708, Edges=5429, Features=1433, Classes=7.  |                            None.                             |
|  2   | Citeseer | [Citeseer](https://linqs.org/datasets/#citeseer-doc-classification) | Nodes=3312, Edges=4591, Features=3703, Classes=6.  | It actually contains 3312 nodes, not 3327 nodes. Seventeen edges are dropped due to the missing nodes, and 124 edges are dropped due to self-loops. After that, 48 isolated nodes occurred. |
|  3   |  Pubmed  | [Pubmed](https://github.com/HazyResearch/hgcn/tree/master/data/pubmed) | Nodes=19717, Edges=44324, Features=500, Classes=3. | 44324 edges remain after removing certain self-loops and duplicate edges. |
|  4   | Airport  | [Airport](https://github.com/HazyResearch/hgcn/tree/master/data/airport) |  Nodes=3188, Edges=18630, Features=4, Classes=4.   | It contains 4 isolated nodes with raw indices {6136, 7217, 7309, 7642}. A self-loop has been removed, reducing the number of edges from 18631 to 18630. |
|  5   |  WebKB   |          [WebKB](https://linqs.org/datasets/#webkb)          |  Nodes=877, Edges=1608, Features=1703, Classes=5.  |                                                              |

