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


### Kernels
- Python 3.9.7
- R 3.2.2
- Julia 1.7.2
- Rust 1.58.1

#### Python Packages (Selected)  
##### Data Wrangling
- Pandas 1.3.4
- Numpy 1.19.5/1.20.3
- Dask 2021.10.0

##### Machine Learning
- Scikit-learn 0.24.2
- Tensorflow 2.4.1
- Pytorch 1.10.2
- Keras 2.6.0

##### Plotting
- Matplotlib 1.1.1
- Seaborn 0.11.2
- Plotly 5.5.0

#### Other Packages of Significance
- JupyterLab 3.2.1
- cudatoolkit 11.1.1

For full list, open a `Terminal` instance and execute `mamba list`.


Last update: 2022-02-20 (DAW)
