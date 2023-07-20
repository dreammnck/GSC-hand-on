# Gcloud command

Create Bucket
```sh
gcloud storage buckets create gs://your_bucket --location=asia-southeast1	--project=poc-innovation-iot --uniform-bucket-level-access 
```

Describe bucket
```sh
gcloud storage buckets describe gs://your_bucket
```

Upload object
```sh
gcloud storage cp ./file1.txt gs://your_bucket
```

Download object
```sh
gcloud storage cp gs://your_bucket/13.png .
```

Describe Object
```sh
gcloud storage objects describe gs://your_bucket/file1.txt
```

List objects
```sh
gcloud storage ls gs://your_bucket
```

Delete object
```sh
gcloud storage rm gs://your_bucket/file1.txt
```

Delete bucket
```sh
gcloud storage buckets delete gs://your_bucket 
or
gcloud storage rm -r gs://your_bucket
```