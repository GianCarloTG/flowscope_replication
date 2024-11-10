## Live-tutorials: Table of Contents



Spartan has compatibility issues with python3.11, to run the code we generate a new kernel

```
conda create --name myvenv python=3.10
activate myvenv
pip install ipykernel
python -m ipykernel install --user --name py310
```
A new kernel in the jupyter notebook will be avialable
Select kernel py310 and import the spartan modules

```bash
   # install spartan using pip
   pip install spartan2
```
```python
   # import spartan package
   import spartan as st
```

Structure of the notebooks:

```
0_Replication_preprocessing: Contanis the preprocessing of the datasets
1_replication_model: Replicates the model by using the dataset preprocessed in notebook 0
2_Flowscope: Replication of the model by using the data sample of the original repository
```
