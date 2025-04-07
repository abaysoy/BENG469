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
