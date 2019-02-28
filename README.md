# cellsite-energy-usage-optimization
* Used clsutering algorithms to optmize energy utilization of cell sites
  * Data munging is performed using Pandas library
  * Clustering is implemented using Kmeans, AgglomerativeClustering, GaussianMixture. Algorithm with lowest silhouette_score is used for clusterign cell sites
 
 * Conclusion
   * Based on utilization and location of cell cites in non-peak hours, 10% of the cell sites can be turned of to save power
