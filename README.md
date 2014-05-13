GoogleBigQuery-multiUpload
==========================

Uploads all Google Analytics Premium tables specfied by a directory to Google Cloud Storage and then loads to Google BigQuery

####Running the Script
```
 ./loadTablesToGoogleBigQuery <source dir> <google cloud storage dir> <bq destionation dataset UID> 
```

#####Additional Notes
```no-highlight
1. Google Analytics Premium tables are in format: ga_sessions_yyyymmdd
2. Google Cloud Storage Bucket must exist and follow format: gs://<mybucket>
3. Google BigQuery Destination DataSet must exit and follow format: <projectId>:<dataSetId>
```
