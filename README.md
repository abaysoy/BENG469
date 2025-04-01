# BENG469 - Lab 8 

# snapATAC environment setup 

salloc  \
module load miniconda  \
conda create -y -n snapATAC python=3.10  \
conda activate snapATAC

pip install anndata==0.8.0 snapatac2==2.4.0 scanpy==1.9.3 scipy pandas==1.5.3 numpy==1.24.3 jupyter notebook  \
ycrc_conda_env.sh update


