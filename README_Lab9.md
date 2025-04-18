# BENG469 - Lab 9 

## SnapATAC_SpatialGlue environment setup 

```
salloc
```
```
module load miniconda
```
```
conda create -y -n snapATAC_SpatialGlue r-base python=3.10
```
```
conda activate snapATAC_SpatialGlue
```
```
pip install anndata==0.8.0 snapatac2==2.4.0 scanpy scipy pandas numpy==1.24.3  rpy2==3.4.1 scikit-learn==1.1.1 tqdm==4.64.0 matplotlib SpatialGlue==1.1.2 scikit-misc==0.2.0 torch jupyter notebook
```
```
ycrc_conda_env.sh update
```







## Copy over the data 
First, Copy ATAC_RNA_Analysis_Workshop over to your Lab9 folder - the scripts are in 02.Scripts. 
```
cd project
```
```
mkdir Lab9 && cd Lab9
```
```
cp -r /vast/palmer/scratch/beng469/beng469_aeb98/ATAC_RNA_Analysis_Workshop ./
```

## SnapATAC Pipeline for ATAC data processing 
Start Jupyter notebook with SnapATAC pipeline \

| **Parameters**      | **Values** |
| ----------- | ----------- |
| Number of hours   | 2        |
| Number of CPU cores per node   | 1        |
| Memory per CPU core in GiB   | 16       |
| Partitions   |  day / education     |

<img width="494" alt="Screenshot 2025-04-03 at 12 19 34 PM" src="https://github.com/user-attachments/assets/eb1752b1-2136-4925-86bd-8eaabb5bb4b0" />

1. Under 02.Scripts, open up 1-SnapATAC.ipynb


## SpatialGlue Lab 
1. Under 02.Scripts, open up 2-SpatialGlue.ipynb


