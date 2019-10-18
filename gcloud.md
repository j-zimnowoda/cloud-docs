In development environment you do not want to keep running VM instancies all the time. You want to keep your mster node up.
In order to not to pay you can resize instance group (k8s worker nodes) to zero.
```
gcloud compute instance-groups managed resize <instance-group-name> --size 0
```
