# ml_intro
ML intro introduce a set of basic machine learning (ml) sessions. Staff is based on samples found over the web.

# First time run
1. Install [miniconda](https://conda.io/miniconda.html)
2. Install [git](https://www.atlassian.com/git/tutorials/install-git)
3. clone project `git clone https://github.com/edystein/ml_intro.git`
4. Create conda environment:
```bash
conda config --add channels conda-forge
conda env create
```

# Regular usage
1. update environment `conda env update`
2. activate environment `source activate ml_intro`
3. Start notebook: 
```bash
 run from cmd: jupyter notebook 
 open localhost:8888
 open and run 01_titanic_features.ipynb
