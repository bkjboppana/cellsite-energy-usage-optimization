# cellsite-energy-usage-optimization
* Used clustering algorithms to optmize energy utilization of cell sites
  * Data munging is performed using pandas and EDA is done using seaborn
  * Clustering is implemented using Kmeans, AgglomerativeClustering, GaussianMixture. Algorithm with lowest silhouette_score is used for clusterign cell sites
 
 * Conclusion
   * Based on utilization and location of cell cites in non-peak hours, 10% of the cell sites can be turned of to save power
