# BENG469 - Lab 8 

# snapATAC environment setup 

salloc  \
module load miniconda  \
conda create -y -n snapATAC python=3.10  \
conda activate snapATAC

pip install anndata==0.8.0 snapatac2==2.4.0 scanpy==1.9.3 scipy pandas==1.5.3 numpy==1.24.3 jupyter notebook  \
ycrc_conda_env.sh update

#SpatialGlue environment setup 
salloc  \
module load miniconda  \
conda create -y -n spatialglue r-base python=3.10  \
conda activate spatialglue

pip install torch scanpy==1.9.1 anndata==0.8.0 rpy2==3.4.1 scikit-learn==1.1.1 tqdm==4.64.0 matplotlib==3.4.2 scipy==1.8.1 pandas==1.4.2 SpatialGlue==1.1.2 scikit-misc==0.2.0 \
ycrc_conda_env.sh update
