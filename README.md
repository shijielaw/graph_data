# shijielaw.data
Some datasets used in my projects.<br>

[Here](https://zhuanlan.zhihu.com/p/361715390) to find the datasets you need...


### 1. Datasets for Node Classification:
| No.  |       Data       |                 Type                 |                             Link                             |                          Statistics                          |                             Note                             |
| :--: | :--------------: | :----------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: |
|  1   |       Cora       | Undirected,  labeled, with features. |           [Cora](https://linqs.org/datasets/#cora)           | Nodes=2708, Edges=5429, Features=1433, Classes=7, Max Degree=168, Min Degree=1. |                      Citation network.                       |
|  2   |     Citeseer     | Undirected,  labeled, with features. | [Citeseer](https://linqs.org/datasets/#citeseer-doc-classification) | Nodes=3312, Edges=4591, Features=3703, Classes=6, Max Degree=99, Min Degree=1. | It actually contains 3312 nodes, not 3327 nodes. Seventeen edges are dropped due to the missing nodes, and 124 edges are dropped due to self-loops. After that, 48 isolated nodes occurred. |
|  3   |      Pubmed      | Undirected,  labeled, with features. | [Pubmed](https://github.com/HazyResearch/hgcn/tree/master/data/pubmed) | Nodes=19717, Edges=44324, Features=500, Classes=3, Max Degree=171, Min Degree=1. | 44324 edges remain after removing certain self-loops and duplicate edges. |
|  4   |     Airport      |       Labeled, with features.        | [Airport](https://github.com/HazyResearch/hgcn/tree/master/data/airport) | Nodes=3188, Edges=18630, Features=4, Classes=4, Max Degree=246, Min Degree=1. | It contains 4 isolated nodes with raw indices {6136, 7217, 7309, 7642}. A self-loop has been removed, reducing the number of edges from 18631 to 18630. |
|  5   |  WebKB-Cornell   |       Labeled, with features.        |          [WebKB](https://linqs.org/datasets/#webkb)          | Nodes=195, Edges=301, Features=1703, Classes=5, Max Degree=94, Min Degree=1. |        301 Edges remain after removing 3 self-loops.         |
|  6   |   WebKB-Texas    |       Labeled, with features.        |          [WebKB](https://linqs.org/datasets/#webkb)          | Nodes=187, Edges=310, Features=1703, Classes=5, Max Degree=104, Min Degree=1. | 310 Edges remain after removing 18 self-loops. It contains 2 isolated nodes |
|  7   | WebKB-Washington |       Labeled, with features.        |          [WebKB](https://linqs.org/datasets/#webkb)          | Nodes=230, Edges=395, Features=1703, Classes=5, Max Degree=122, Min Degree=1. | 395 Edges remain after removing 51 self-loops. It contains 13 isolated nodes |
|  8   | WebKB-Wisconsin  |       Labeled, with features.        |          [WebKB](https://linqs.org/datasets/#webkb)          | Nodes=265, Edges=510, Features=1703, Classes=5, Max Degree=122, Min Degree=1. | 510 Edges remain after removing 20 self-loops. It contains 3 isolated nodes |
|  9   |       AIDS       | Undirected, labeled, with features.  |        [AIDS](https://networkrepository.com/AIDS.php)        | Nodes=31385, Edges=32390, Features=4, Classes=38, Max Degree=6, Min Degree=2. | Half of edges remain due to the duplicate edges, e.g., (2, 1) should be remove when (1, 2)  in edge list. It contains 210 isolated nodes |

