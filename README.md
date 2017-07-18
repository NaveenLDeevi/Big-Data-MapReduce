# Big-Data-Page-Rank
In this part, you will implement a MapReduce-based commonly-used web link analysis
algorithm: PageRank. For the formula of PageRank, please refer to the slides.
TODO
1. Write a MapReduce program to calculate PageRank value for each node. Your program
must have the following:
a. input : Download input_pagerank.txt through Blackboard. The input is
adjacency list of pages shown as following,
node1<\tab>outlink_node11,outlink_node12,...
node2<\tab>outlink_node21,outlink_node22,...
…
In other words, node1->outlink_node11, node1->outlink_node12, etc
b. maxIter : Stop criterion. For simplicity, stop after a certain number of iterations.
Set maxIter=10 .
c. beta . The damping factor. Set β=0.85 .
d. output : Nodes followed by their PageRank value.
node1<\tab>PageRank score
node2<\tab>PageRank score
…
