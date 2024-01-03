# Application-of-k-means-and-tabu-search-algorithms-in-optimization.
---

## Overview.
My project focuses on optimizing transportation logistics through the integration of two powerful algorithms: K-means clustering and Tabu Search. Leveraging the efficiency of K-means, our system intelligently groups delivery locations based on geographical proximity, streamlining the overall transportation network. Subsequently, the Tabu Search algorithm is employed to address the complex optimization problem within the transportation route. This heuristic search method iteratively explores solution spaces, avoiding local optima through strategic memory management. The synergy between K-means and Tabu Search not only enhances the overall efficiency of transportation planning but also contributes to significant cost reductions and resource optimization. The project represents a cutting-edge approach to tackling the challenges in transportation logistics, promising innovative solutions for industries reliant on streamlined and optimized supply chains.
## Description.
My project involves a dataset representing various customer locations and a central depot. The objective is to optimize the delivery process by frist applying the K-means clustering algorithm to group customer locations into clusters based on proximity to each other in terms of coordinates. After clustering, the project focuses on achieving a balanced distribution of customer points across these cluters. This ensures that each cluster has an approximately number of customer locations.
finally, the Tabu Search algorithm is employed to find the most optimal routes for each cluster. Tabu Search is a heuristic optimization method that explores the solution shortest route.

![alt text](https://github.com/tranhuuan1703/Application-of-k-means-and-tabu-search-algorithms-in-optimization./blob/main/workflow_optimizer_vrp.drawio.png)
## Result and experiment.
I tried testing on three different classification algorithms: K-means, Genetic, Kmedoids. The result of K-means algorithm best of three algorithm.</br>
**_NOTE:_**  Testing in dataset GPS.</br>

Algorithm  | distance total |
------------- | --------------|
K-means | 1038/km |
Genetic  | 83526/km |
Kmedoids  | 1038/km | 

**_Note_**: balanced on kmeans algorithm. Between random clustering and uniform clustering.Testing in dataset datasample 2<br>

Algorithm | distance total| times |
----------|---------------|-------|
K-means balance|141/km|~8s|
K-means not balance|159/km| ~37s|

### out image.

| ![alt text](https://github.com/tranhuuan1703/Application-of-k-means-and-tabu-search-algorithms-in-optimization./blob/main/output_kmeans_balance.png)|
|:---:|
|*output k-means balane*|
![alt text](https://github.com/tranhuuan1703/Application-of-k-means-and-tabu-search-algorithms-in-optimization./blob/main/output_kmean_not.png)
*output k-means not balane*
