# Setup NFS Service in K8s and use in PV & PVC
## Sequence Steps ##
create_disk00.sh -> create a GCE Disk
nfs-service01.yaml -> create NFS POD
nfs-svc02.yaml -> create NFS Service
nfs-pv-pvc03.yaml -> Expose NFS mount in PV & PVC
nfs-pod04.yaml -> Test POD using PVC
nfs-nginx05.yaml -> Test Nginx service using webroot using PVC
