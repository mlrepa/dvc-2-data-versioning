# Lesson 2 tutorial: Versioning Data and Model 
**ML REPA School course**: Machine Learning experiments reproducibility and engineering with DVC

## 1. Clone this repository

```bash
git clone https://github.com/mlrepa/dvc-2-data-versioning.git
cd dvc-2-data-versioning
```

## 2. Create and activate virtual environment

Install virtualenv in advance: 

```bash
pip install virtualenv
```

Create virtual environment named `dvc` (you may use other name)
```bash
virtualenv dvc
source dvc/bin/activate
```

## 3. Install python libraries

```bash
pip install -r requirements.txt
```

    
## 4. Add Virtual Environment to Jupyter Notebook

```bash
python -m ipykernel install --user --name=dvc
``` 

## 5. Configure ToC for jupyter notebook (optional)

```bash
sudo jupyter contrib nbextension install
jupyter nbextension enable toc2/main
```

## 6. Run and follow Jupyter Notebook `dvc-2-data-versioning.ipynb` for instructions:

```bash
jupyter notebook
```
