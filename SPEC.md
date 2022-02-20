# LAW Data Bootcamp VM
  
### VM Spec
- Host: Google Cloud - asia-southeast2-b (Jakarta)
- CPU*: 2vCPU (Intel Xeon @2.20GHz); `avx`,`avx2` enabled
- RAM*: 4GB
- OS: Ubuntu 20.04.3 LTS (Focal Fossa)
- Storage*:
    - OS: 32GB
    - Data: 32GB
- GPU*: **None**

*Adjustable

#### Storage
An data disk has been attached at `/mnt/data` and symlinked to `/home/law/bootcamp`. This JupyterLab instance is set to have a home directory at `/home/law/bootcamp`. Daily snapshots/increment made for both OS and data disks, with a retention period of 3 days.



### Access
IP whitelisting - HL14 network and DAW VPN only.  
Additional IP whitelisting can be made via Google Cloud Console.


