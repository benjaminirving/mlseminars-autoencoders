# mlseminars-autoencoders

Slides for my autoencoder seminar

Notebook can be viewed in github by clicking on [Autoencoders.ipynb](https://github.com/benjaminirving/mlseminars-autoencoders/blob/master/Autoencoders.ipynb)

## How to run these slides and examples yourself

**Setup python environment**

- Jupyter notebook
- Requirements: `numpy`, `keras`, `theano`, `jupyter`
- Python 3
- Probably Python 2 as well but I haven't bothered to test -- everyone should be using python 3 ;)
- Install RISE for an interactive presentation viewer 
  - see install instructions here (https://github.com/damianavila/RISE) 

**Get**
```bash
# Clone the repository
git clone https://github.com/benjaminirving/mlseminars-autoencoders
cd mlseminars-autoencoders
```

**Run**
```
jupyter notebook
```

**View in presentation mode using RISE**
After running the notebook, click on the RISE button

or
```
jupyter nbconvert --to slides Autoencoders.ipynb --post serve
```


