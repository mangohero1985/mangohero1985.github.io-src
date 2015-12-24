title: Distance Metrics
category: Machine Learning
slug: distance_metics
Data: 2015/12/11
Authors: Mango
Modified: 2015/12/15
Tags: Unsupervised, Clustering
Summary:  We are intruducing some distance metrics which are commonly used on measure similarity in machine learning.

## Metrics Space
Given a set ***X***, ***X*** is a metirc space if it keeps to a function ***d(x,y)*** that can measure the distance between any two points ***x*** , ***y*** in space of ***X***. Then, ***d*** must satisfy the axioms of the metrics:

* Non-negativity: ***d(x,y)>=0***, ***d(x,y)=0*** if and only if ***x=y*** 
* Symmetry: ***d(x,y)=d(y,x)***
* Triangle inequality: ***d(x,y)+d(y,z) >= d(x,z)***


## <a name="Minkowski_distance"></a>Minkowski distance
**Minkowski dishtance** is the most common distance measure method, there are two points ***x*** , ***y*** as follows:
![Minkowski1](/images/Minkowski_distance_1.png)
![Minkowski2](/images/Minkowski_distance_2.png)

Here, if the ***P*** is 2, Minkowski distance would be [Euclidean distance](#Euclidean_distance). If the ***P***  is 1, it would be Manhanttan distance.

###<a name="Euclidean_distance"></a>Euclidean distance
**Euclidean distance** is the "ordianary" disctance between two points in Euclidean space. The points in Euclidean space (N-Space) are called Euclidean vectors. The Euclidean distance of vector of vector ***P*** and vector ***Q*** can be computed as follows:
![Euclidean](/images/Euclidean_distance.png)


### <a name="Manhattan_distance"></a>Manhattan distance(Texicab geometry)
**Manhattan distance** is a form of geometry in which the usual distance function of metric or Euclidean geomery us replaces by a new metirc in which the distance between two points is the sum of the absolute differences of their [Carteisan coordinates](https://en.wikipedia.org/wiki/Cartesian_coordinate_system). Manhatten distance is also known as rectilinear distance L1 distance.

![Manhattan_dis](/images/Manhattan_dis.png)

###<a name="Chebyshev_distance"></a>Chebyshev distance

If ***P*** tends to be infinite, **Minkowski distance** would be **Chebyshev distance**. It can be expressed as: 
![chevi_dis](/images/Chebyshev_distance.png)


### Extends for Minkowski distance
In plain, if the Euclidean distance is set as 1, when ***p*** is 2, the figure would be a round. Thus, what the figures would be when ***p*** is the other value?
![p_diff](/images/p_diff.png)

Commonly, before we are going to use **Minkowski distance**, a regularion method named **"z-transform"** is adopted:
![z-trans](/images/z-trans.png)
mu: the mean in that dimention  
sigma: the variance in that dimention
















=======
>>>>>>> a285ab651fa2f537e0c1a7a00d97b05b84db7b8b

## Euclidean Distance
**Euclidean distance** is the "ordianary" disctance between two points in Euclidean space. The points in Euclidean space (N-Space) are called Euclidean vectors. The Euclidean distance of vector of vector ***P*** and vector ***Q*** can be computed as follows:
![Euclidean](/images/Euclidean_distance.png)