# Apachebeam
## Environmet Setup
### 1. Make a python virtual environmet
#### Debian:
       mkdir apache
       python3 -m venv apache
       source python/bin/activate
       pip install jupyterlab
       pip install apache-beam
       pip install apache-beam[gcp] mysql-connector-python
#### To run the code, start your lab using the command bellow in the virtual environment
      jupyter-lab
