The json provided in this directory according to this hierarchy of keys:
* Keys at depth 1 indicate the clustering algorithm (`'pattern clustering'`, `'LogMine'`, `'Drain'`);
* Keys at depth 2 indicate the considered dataset (`'Apache'`, `'HDFS'`, `'Spark'`, `'Zookeeper'`, `'Thunderbird'`, `'BGL'`, `'Proxifier'`, `'HealthApp'`, `'Andriod'`, `'Windows'`, `'HPC'`, `'Hadoop'`, `'OpenSSH'`, `'Linux'`, `'Mac'`, `'OpenStack'`);
* For Pattern Clustering and LogMine, the keys at depth 3 indicate the threshold parameter (`'0.01'`, `'0.05'`, `'0.1'`, `'0.2'`, `'0.3'`, `'0.4'`, `'0.5'`, `'0.6'`, `'0.7'`, `'0.8'`, `'0.9'`, `'0.99'`);
* For drain, keys at depth 3 (resp. 4) correspond to the two parameters `'sim_th'` (`'0.01'`, `'0.05'`, `'0.1'`, `'0.2'`, `'0.3'`, `'0.4'`, `'0.5'`, `'0.6'`, `'0.7'`, `'0.8'`, `'0.9'`, `'0.99'`) and `'depth'` (`'3'`, `'4'`, `'5'`, `'6'`);
* For all algoritms, The last level of keys report the performance metrics evaluated during our experiments (`'parsing accuracy'`, `'adjusted rand index'`, `'time'`, `'number of clusters'`).
