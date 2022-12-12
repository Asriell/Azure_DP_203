# Azure_DP_203
+ Once a database has been created by a Spark job, you can create tables in it with Spark that use Parquet as the storage format. Table names will be converted to lower case and need to be queried using the lower case name. These tables will immediately become available for querying by any of the Azure Synapse workspace Spark pools. They can also be used from any of the Spark jobs subject to permissions.

+ Supprimer efficacement des données par partitions : 

  + Creer une table vide temporaire
  + mettre les données à supprimer dedans
  + drop la table
  
+ **Temps réel** : 
  + Input type = Stream, Function = Geospatial
+  Optimisation de perf : paralleliser Input et Output
+  Tumbling windows are a series of fixed-sized, non-overlapping and contiguous time intervals.
+  Azure Data Factory pipelines can execute SSIS packages. In Azure, the following services and tools will meet the core requirements for pipeline orchestration, control flow, and data movement: Azure Data Factory, Oozie on HDInsight, and SQL Server Integration Services (SSIS).
+  Data Lake Storage Gen1 provides unlimited storage.
+  
