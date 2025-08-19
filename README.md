# open_storage_network

University of Arizona hosts an [Open Storage Network (OSN)](https://www.openstoragenetwork.org/) pod on campus at UITS. The pod is ~ 1.4 petabytes of S3 cloud storage. 400 TBs has been given over to the OSN for communial use. 

Managing allocations, storage buckets, and users is done through the user interface [Coldfront](https://coldfront.osn.mghpcc.org/). Credentials are through NSF ACCESS similar to Jetstream2. Coldfront [documentation](https://coldfront.osn.mghpcc.org/static/gen2docs/index.html)

Reading and writing to buckets is done through command line tools like [rclone](https://openstoragenetwork.github.io/docs/dataset-access/rclone/)


Copy file from local to cloud bucket
`rclone copy /local/file.txt arizona_osn_lib:/ual`



