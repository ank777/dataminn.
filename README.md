# dataminn.
Data Mining Project
In machine learning there are various type of learning supervised,unsupervised and reinforcement learning.
In these unsupervised learning plays a major role. Here,clustering various algorithms  are used.
Among all of the techniques the partition based clustering is extensively used.For example K -means,fuzzy C-means  are popular algorithms.


The traditional fuzzy c-means (FCM) operates when cluster number c is assigned. 
The value of c makes a great influence on the cluster result. However, the value of cluster number cannot be confirmed automatically and needs to be input manually which results in hinderance when using the fuzzy c-means.
Through improved method it helps us to find the optimal value.


K-means algorithms(standard)

1.Choose k cluster center initially.

2.Assign each point to nearest cluster center

3.Re calculate cluster center.

4.If convergence criteria is met then stop else go to 

   step 2.

In case of Fuzzy c-means varies while assigning membership value

to each cluster center.

Algorithm for choosing initial cluster value(c)

A.	Intialize c=2

B.	For each c value:

              For k >=2 :
                  
                  Calculate average of distance 
                  
                  of k nearest  neighbours from  Ci 
              k++
      c++       
     Divide distace by number of cluster center (c)
Calculate min distance between Ci and Ci-1,choose 
  Ci-1 if value is globally minimum for minimum data set.



