# jupyter-notebook-with-virtual-env
Steps to use virtual environment with jupyter notebook  


$ python -m venv projectname
$ source projectname/bin/activate
(venv) $ pip install ipykernel
(venv) $ ipython kernel install --user --name=projectname
