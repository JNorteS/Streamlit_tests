# Config Streamlit_tests

## Open jupyter lab through anaconda prompt
jupyter lab 

## Jupyter environment

```bash

pip install --upgrade jupyterlab jupyterlab-git notebook
conda init powershell
Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy Unrestricted

```

## Environment creation

```bash

# Execute "Anaconda Prompt" through windows search

# Environment creation in the Anaconda Prompt
conda create -n my_env python=3.12 ipykernel -y
conda activate my_env

pip install streamlit

# Publicació del kernel
python -m ipykernel install --user --name my_env --display-name "my_env"
pip freeze > configuration\requirements.txt

```

## Git clone

```bash

# Execute Jupyter through window search

# Substitute "tree" by "lab" http://localhost:8888/tree --> http://localhost:8888/lab

# INFO: Root directory C:\Users\34687

git clone https://github.com/JNorteS/Streamlit_tests.git

```

## App run

```bash

conda activate my_env
streamlit run tasks\app.py

```
