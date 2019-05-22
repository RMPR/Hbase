# Hbase presentation
## Prerequisites
```bash
pip3 install jupyter --user # jupyter notebook for python3
pip3 install RISE --user # modify the slideshown while viewing
jupyter-nbextension install rise --py --sys-prefix

```
## Running environnement
```bash
git clone https://github.com/RMPR/Hbase.git
cd Hbase
jupyter notebook Hbase.ipynb # for the jupyter notebook
jupyter nbconvert Hbase.ipynb --to slides --post serve # for the slideshow
```

## Contributing 
First you need to create a branch according to the feature you are working on
    git checkout -b <branch_name>


