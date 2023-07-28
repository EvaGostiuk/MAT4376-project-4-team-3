## Algorithms Used to Detect Outliers/Anomalous Datapoints

Using at least 4 anomaly detection algorithms seen in class, identify anomalous observations in the dataset. 
The outliers identified in each anomaly detection algorithm is based on the unique "X" value assigned to each unit in the subset.


### Principle Component Analysis (PCA)
Outliers Identified:
93182
477922
259286
467791
42767
479941
312513
381994
451093
259423
270720
352242
382028
46425
93004

### Subspace Outlier Detection (SOD) Algorithm
Outliers Identified:
259286
467279
42767
477922
93182
527628
381994
467791
312513
467358

### Density-Based Spatial Clustering of Applications with Noise (DBSCAN)
Outliers Identified:
490158, 259286, 282050, 113891, 473726, 250208, 42767, 219580, 239692, 477922, 93182, 259372, 417185, 449318, 210546, 469875, 54463, 354955, 529616, 479941, 467791, 544652, 240, 469356, 171352, 256452, 228490, 526012, 82692, 11902, 501614, 492652, 121347, 77196

### K-Nearest Neighbours (KNN)
Outleirs Identified:
259286, 282050, 113891, 473726, 42767, 239692, 477922, 93182, 259372, 417185, 449318, 381994, 337032, 354955, 529616, 479941, 467791, 268199, 544652, 171352, 256452, 228490, 266925, 262613, 82692, 502920, 501614, 121347, 77196, 454429, 92801

### Common by all methods:
{42767, 93182, 259286, 467791, 477922, 479941}
