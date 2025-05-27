# kmeans-excel

## Description
This project implements the K-Means clustering algorithm using Microsoft Excel.  
The dataset contains 7 two-dimensional data points (X, Y), with the number of clusters (k) set to 3.  
The initial centroids are manually defined as follows:
- C1 = (500, 5000)  
- C2 = (300, 3000)  
- C3 = (20, 40)  

## Clustering Process
Clustering is done iteratively by calculating Euclidean distances and assigning each point to the nearest centroid.

The cluster distribution for each iteration is as follows:

| Iteration | Cluster 1 (C1) | Cluster 2 (C2)       | Cluster 3 (C3)                |
|-----------|----------------|----------------------|-------------------------------|
| 1         | {}             | {}                   | {M1, M2, M3, M4, M5, M6, M7}  |
| 2         | {}             | {M4, M5, M6, M7}     | {M1, M2, M3}                  |
| 3         | {}             | {}                   | {M1, M2, M3, M4, M5, M6, M7}  |
| 4         | {}             | {}                   | {M1, M2, M3, M4, M5, M6, M7}  |

## Conclusion
The final result shows all data points converging into Cluster 3 due to the distant initial positions of C1 and C2.  
Full centroid recalculations for each iteration are available in the Excel file.

## How to Use
1. Download the Excel file from this repository.  
2. Open the file in Microsoft Excel.  
3. Review the worksheets to see iteration steps and centroid updates.

## Author
This project was created to practice course material as part of a college assignment.
