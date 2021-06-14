# storage-k8s

- used with ArgoCD to manage ressources, mostly Helm charts. Everything helm related is `spec.source.helm.values`
- the rook-operator processes a `storage/rook-cluster.yaml`
- I use a `storage/rook-ceph-fs` CephFilesystem and `storage/ceph-fs-storage class`
- this is a bare metal install with 3x SSD partition for metadata and 6x 2TB HDD for storage
