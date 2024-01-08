# shijielaw.data
Some datasets used in my projects.<br>

[Here](https://zhuanlan.zhihu.com/p/361715390) to find the datasets you need...<br>

【Note】For undirected graph, duplicated edges are removed here, e.g., (2, 1) should be removed when (1, 2)  in edge list. For each graph, self-loops are cleaned. 




### 1. Datasets for Node Classification:
| No.  |   Data   |                 Type                 |                             Link                             |                          Statistics                          |                             Note                             |
| :--: | :------: | :----------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: |
|  1   |   Cora   | Undirected,  labeled, with features. |           [Cora](https://linqs.org/datasets/#cora)           | Nodes=2708, Edges=5278, Features=1433, Classes=7, Max Degree=168, Min Degree=1. | 5278 edges remain due to the 151 duplicate edges. No isolated node here. |
|  2   | Citeseer | Undirected,  labeled, with features. | [Citeseer](https://linqs.org/datasets/#citeseer-doc-classification) | Nodes=3312, Edges=4536, Features=3703, Classes=6, Max Degree=99, Min Degree=1. | It actually contains 3312 nodes, not 3327 nodes. Seventeen edges are dropped due to the missing nodes, and 56 duplicated edges  and 124 self-loops are dropped. After that, 48 isolated nodes occurred and they are indexed to the last 48. |
|  3   |  Pubmed  | Undirected,  labeled, with features. | [Pubmed](https://github.com/HazyResearch/hgcn/tree/master/data/pubmed) | Nodes=19717, Edges=44324, Features=500, Classes=3, Max Degree=171, Min Degree=1. | 44324 edges remain after removing certain self-loops and duplicate edges. No isolated node here. |
|  4   | Airport  | Undirected,  labeled, with features. | [Airport](https://github.com/HazyResearch/hgcn/tree/master/data/airport) | Nodes=3188, Edges=18571, Features=4, Classes=4, Max Degree=246, Min Degree=1. | A self-loop and 59 duplicated edges have been removed, reducing the number of edges from 18631 to 18571. After that, 12 isolated nodes occurred and they are indexed to the last 12. |
|  5   |   AIDS   | Undirected, labeled, with features.  |        [AIDS](https://networkrepository.com/AIDS.php)        | Nodes=31385, Edges=32390, Features=4, Classes=38, Max Degree=6, Min Degree=2. | Half of edges remain due to the duplicate edges, e.g., (2, 1) should be removed when (1, 2)  in edge list. It contains 210 isolated nodes. |

