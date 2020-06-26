# dvc-lesson-3

## 1. clone this repository

```bash
git clone https://gitlab.com/7labs.ru/tutorials-dvc/dvc-2-data-versioning.git
cd dvc-2-data-versioning
```

## 2. Create and activate virtual environment

Install virtualenv in advance: 

```bash
pip install virtualenv
```

Create virtual environment 
```bash
virtualenv venv-dvc-2-data-versioning
source venv-dvc-2-data-versioning/bin/activate
```

## 3. Install python libraries

```bash
pip install -r requirements.txt
```

    
## 4. Add Virtual Environment to Jupyter Notebook

```bash
python -m ipykernel install --user --name=venv-dvc-2-data-versioning
``` 

## 5. Configure ToC for jupyter notebook

```bash
sudo jupyter contrib nbextension install
jupyter nbextension enable toc2/main
```

## 6. Run and follow Jupyter Notebook `Lesson 3.ipynb` for instructions:

```bash
jupyter notebook
```
