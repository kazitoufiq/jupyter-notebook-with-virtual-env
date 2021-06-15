# jupyter-notebook-with-virtual-env



## Linux/Ubuntu

### best-practice is to ensure all packages are up to date
apt-get update -y

### install python3-venv
apt-get install -y python3-venv


## Steps to use virtual environment with jupyter notebook  


python3 -m venv py_venv

source py_venv/bin/activate

pip3 install ipykernel

ipython kernel install --user --name=py_venv
