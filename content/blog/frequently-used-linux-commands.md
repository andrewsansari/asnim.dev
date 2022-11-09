+++
title = "Frequently used linux commands"
date = "2022-11-09"
draft = false
+++


Dumping some linux commands which I often use so that I dont have to Google again

1. rsync a folder to GCP Public Bucket
```
gsutil -m rsync -d -r public gs://<bucket-name>
```

2. ssh with a key file
```
ssh -i <key file path> user@host
```

3. Copy file from local to remote server
```
scp file.txt remote_username@10.10.0.2:/remote/directory
```