GoogleBigQuery-multiUpload
==========================

Uploads all Google Analytics Premium tables specfied by a directory to Google Cloud Storage and then loads to Google BigQuery

####Running the Script
```
 ./loadTablesToGoogleBigQuery <source dir> <google cloud storage dir> <bq destionation dataset UID> 
```

#####Additional Notes
```
1. Google Cloud SDK/BigQuery Command Line tool must be previously installed 
2. gsutil must be previously installed 
3. Google Analytics Premium tables are in format: ga_sessions_yyyymmdd
4. Google Cloud Storage Bucket must exist and follow format: gs://<mybucket>
5. Google BigQuery Destination DataSet must exit and follow format: <projectId>:<dataSetId>
```

`Tested with BigQuery CLI 2.0.19`
`Tested with gsutil version 3.42`
