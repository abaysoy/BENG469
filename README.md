# BENG469 - Lab 8 

## SnapATAC environment setup 

```
salloc  
module load miniconda  
conda create -y -n snapATAC python=3.10  
conda activate snapATAC

pip install anndata==0.8.0 snapatac2==2.4.0 scanpy==1.9.3 scipy pandas==1.5.3 numpy==1.24.3 jupyter notebook  
ycrc_conda_env.sh update
```

##  SpatialGlue environment setup 
```
salloc  
module load miniconda  
conda create -y -n spatialglue r-base python=3.10  
conda activate spatialglue


pip install torch scanpy==1.9.1 anndata==0.8.0 rpy2==3.4.1 scikit-learn==1.1.1 tqdm==4.64.0 matplotlib==3.4.2 scipy==1.8.1 pandas==1.4.2 SpatialGlue==1.1.2 scikit-misc==0.2.0 jupyter notebook
ycrc_conda_env.sh update

```

## Copy over the data 
First, Copy ATAC_RNA_Analysis_Workshop over to your Lab8 folder - the scripts are in 02.Scripts. 
``` /home/beng469_aeb98/project/Lab8/ATAC_RNA_Analysis_Workshop ```

## SnapATAC2 Pipeline for ATAC data processing 
Start Jupyter notebook with SnapATAC pipeline \
![Screenshot 2025-04-02 at 10 26 30 AM](https://github.com/user-attachments/assets/1c6ce0e6-4c45-4fbf-a550-edc10b6a1648) \

1. Under 02.Scripts, open up 1-SnapATAC_011525.ipynb


## SpatialGlue Lab 
1. Under 02.Scripts, open up 2-SpatialGlue.ipynb
