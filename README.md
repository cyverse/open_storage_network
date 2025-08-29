# open_storage_network

University of Arizona hosts an [Open Storage Network (OSN)](https://www.openstoragenetwork.org/) pod on campus at UITS. The pod is ~ 1.4 petabytes of S3 cloud storage. 400 TBs has been given over to the OSN for communial use. Most users of the OSN pod will do so through NSF ACCESS-CI. For our colleagues at UA, we may provide storage buckets without using ACCESS-CI

Managing allocations, storage buckets, and users is done through the user interface [Coldfront](https://coldfront.osn.mghpcc.org/). Credentials are through NSF ACCESS similar to Jetstream2. Coldfront [documentation](https://coldfront.osn.mghpcc.org/static/gen2docs/index.html)

Reading and writing to buckets is done through command line tools like [rclone](https://openstoragenetwork.github.io/docs/dataset-access/rclone/) or [AWS CLI](https://openstoragenetwork.github.io/docs/dataset-access/aws-cli/)

Find the rclone config file on your machine `rclone config file`

Copy file from local to cloud bucket
`rclone copy /local/file.txt <bucket_alias>:/<bucket_name`

`rclone copy /home/jgillan/Downloads/collection25.json arizona_osn_lib:/ual`



