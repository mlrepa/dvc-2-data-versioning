# dvc-lesson-3

## 1. clone this repository

```bash
git clone https://gitlab.com/7labs.ru/tutorials-dvc/dvc-lesson-3.git
cd dvc-lesson-3
```

## 2. Create and activate virtual environment

Install virtualenv in advance: 

```bash
pip install virtualenv
```

Create virtual environment 
```bash
virtualenv venv-lesson3
source venv-lesson3/bin/activate
```

## 3. Install python libraries (including dvc)

```bash
pip install -r requirements.txt
```

    
## 4. Add Virtual Environment to Jupyter Notebook

```bash
python -m ipykernel install --user --name=venv-lesson3
``` 

## 5. Run and follow Jupyter Notebook `tutorial.ipynb` for instructions:

```bash
jupyter notebook


