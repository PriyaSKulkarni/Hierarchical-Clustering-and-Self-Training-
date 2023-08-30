# Hierarchical-Clustering-and-Self-Training-
CSE-6363-001-MACHINE LEARNING under Manfred Huber: Hierarchical Clustering and Self-Training 

**Hierarchical Clustering:**
1. Examining unlabeled data from Question 2c:
a) Implement hierarchical agglomerative clustering with options for single (minimum) and complete (maximum) linkage.
b) Apply hierarchical clustering with single linkage to the data. Evaluate cluster purity for 2, 4, 6, and 8 clusters by computing cluster accuracy based on most frequent label. Calculate overall accuracy using cluster weights as data point fractions. 
c) Repeat clustering and evaluation from part 1b using complete linkage. Compare single and complete linkage results, discussing differences in reflecting material types.

**Self-Training:**
2. Using data from Question 2c, separate supervised and unsupervised data:
a) Implement a self-training system using a K-nearest neighbor classifier. Incorporate a certainty evaluation metric, like purity or distance-weighted voting. Allow iteration-wise addition of data items to the labeled set.
b) Employ the semi-supervised learning algorithm and compare it against a K-nearest neighbor classifier trained only on labeled data. Evaluate the fraction of initially unlabeled points predicted correctly. Perform the comparison for different iteration-wise data additions and discuss observed performance differences.

In summary, we explore hierarchical clustering, evaluating its outcomes under different linkage criteria. We then delve into self-training using a K-nearest neighbor classifier, comparing it against a fully supervised K-nearest neighbor classifier, and discussing the impact of iteration-wise data addition on performance.
