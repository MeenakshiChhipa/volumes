# Volumes Configurations Steps :

1. We have to create a EBS Volume Lets say 5GB.

2. In PV we are mention this EBS volume ID So we can get storage from EBS.

3. The main point if we use EBS Volume we nerver loose data because here we are mentioning mountpath.

4. Note : hostpath volume is connected with one node we can not use this volume because if a pod is deleted any reason and it created on another node here a problem we can not get previous data.
