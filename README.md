# dataminn.
data mining project
In machine learning there are various type of learning supervised,unsupervised,Reinforcement learning.
In which unsupervised learning plays a major role. In unsupervised learning clustering various algorithms  are used.
Among all of the techniques the partition based clustering is extensively used for example K -means,fuzzy C-means  are popular algorithms.


The traditional fuzzy c-means (FCM) operates when cluster number c is assigned. 
The value of c makes a great influence on the cluster result. However, the value of cluster   number cannot be confirmed automatically and needs to be input manually.
which results in hinders when using the fuzzy c-means.
Improved method helps us to find the optimal value.


K-means algorithms(standard)

1.Choose k cluster center initially.

2.Assign each point to nearest cluster center

3..Re calculate cluster center.

4.if convergence criteria is met then stop else go to 

   step 2.

in case of Fuzzy c-means varies while assigning membership value

to each cluster center.

Algorithm for choosing initial cluster value(c)

A.	Intilize c=2

B.	For each c value:

              For k >=2 :
                  
                  Calculate average of distance 
                  
                  of k nearest  neighbours from  Ci 
              k++
      c++       
     Divide distace by number of cluster center (c)
Calculate min distance between Ci-Ci-1 choose 
  Ci-1 if value is globally minimum for minimum data set.



