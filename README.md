# Lab 10 
## Create environment for maxfuse
```
salloc
```
```
module load miniconda
```
```
git clone https://github.com/shuxiaoc/maxfuse.git
```
```
conda create -y -n maxfuse python=3.8
```
```
conda activate maxfuse
```
```
python -m pip install maxfuse jupyter notebook 
```

```
module purge
```
```
ycrc_conda_env.sh update
```
## Copy over the data 
```
cd project 
```

```
cp -r /vast/palmer/scratch/beng469/beng469_aeb98/Lab10 ./
```

## Open Jupyter notebook using the following parameters: 
<img width="542" alt="Screenshot 2025-04-07 at 1 23 34 PM" src="https://github.com/user-attachments/assets/764976d4-753f-47bf-ba48-6afef99aaa8f" />
