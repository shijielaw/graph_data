ind.dataset_str.x => the feature vectors of the training instances as scipy.sparse.csr.csr_matrix object;
ind.dataset_str.tx => the feature vectors of the test instances as scipy.sparse.csr.csr_matrix object;
ind.dataset_str.allx => the feature vectors of both labeled and unlabeled training instances
(a superset of ind.dataset_str.x) as scipy.sparse.csr.csr_matrix object;
ind.dataset_str.y => the one-hot labels of the labeled training instances as numpy.ndarray object;
ind.dataset_str.ty => the one-hot labels of the test instances as numpy.ndarray object;
ind.dataset_str.ally => the labels for instances in ind.dataset_str.allx as numpy.ndarray object;

ind.dataset_str.graph => a dict in the format {index: [index_of_neighbor_nodes]} as collections.defaultdict object;
ind.dataset_str.test.index => the indices of test instances in graph, for the inductive setting as list object.


np.vstack((ally, ty))就是按照节点标识符顺序（0-191716）所对应的标签。
sp.vstack((allx, tx)).tolil()就是按照节点标识符顺序（0-191716）所对应的特征矩阵。
graph为图的dict_of_lists.