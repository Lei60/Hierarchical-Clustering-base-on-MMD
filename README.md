# Hierarchical-Clustering-base-on-MMD
Using MMD to calculate the similarity

基于mmd的层聚类方法

当每个data point为一组数据时，一般会使用均值带代表整组数据，通过计算距离来计算相似度

这里考虑均值不能很好的代表整组数据时，使用mmd可以input整组数据，利用更多的信息去计算相似度

优点：可以input整组数据，使用更多信息去计算相似度

缺点：

1.当数据量过大时会占用大量的GPU内存

2.层聚类可能会导致分到每个group的data point不均匀
