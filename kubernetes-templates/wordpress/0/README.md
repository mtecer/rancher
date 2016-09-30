# Persistent Installation of MySQL and WordPress on Kubernetes

## Requirements:
1. NFS shares needs to be provisioned before stack creation:
    - /nfs/exports/kube-mysql-`${cluster_name}`
    - /nfs/exports/kube-wordpress-`${cluster_name}`
