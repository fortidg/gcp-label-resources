# Label GCP Resources

This document will cover how to add a label to GCP Resources.  This is part of the cost savings project to reduce unused resources in GCP.  Only resources containing the appropriate label will be preserved.  All other resources will be deleted.

> [!NOTE]
> Labels are key-value pairs that can be used on Google Cloud to group related or associated resources. For example, on Compute Engine, you can use labels to group VMs in categories such as production, staging, or development so that you can search for resources that belong to each development stage. After adding labels to your resources, you can take advantage of the nested filtering feature to perform more precise searches for your resources using labels.

For the purposes of this exercise, all VM Instances, GKE clusters, disks and storage buckets will need to be labeled.  The below sections highlight this process.

> [!Important]
> The label key will be **keep_resource** the label value will be **true**