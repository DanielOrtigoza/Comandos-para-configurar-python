# Configurar Python Anaconda

Comandos básicos de Anaconda 

`conda --version`: comando para ver la versión actual de Anaconda

`conda rename -n old_name new_name`: comando para renombrar un ambiente virtual

Comandos para correr en anaconda cuando creo un ambiente virtual donde “nombre” corresponde al nombre del ambiente virtual

`conda create -n “nombre”`

`conda env list`

`conda env remove --name  “nombre”`

`conda activate “nombre”`

`conda update --all` → actualizar todos los paquetes

`conda install python`

`conda install -n base -c defaults conda = 23.3.1` → para correr este comando tengo que estar en otro ambiente virtual, también especifico la versión que deseo

`conda install -c anaconda pandas`

`conda install -c anaconda numpy`

`conda install -c conda-forge matplotlib`

`conda install -c conda-forge imbalanced-learn`

`conda install -c conda-forge jupyterlab`

`pip install db-dtypes google google-cloud google-cloud-bigquery google-auth`

`pip install ipympl`