# T01-nvidia-jupyternotebookenv

## Environment set up for developers of this tool
1. Set up python virtual environment, in same directory, type in command prompt `python3.8 -m venv venv`
2. Run command below to activate venv

|Windows|Linux/Mac|
|--|--|
|.\venv\Scripts\activate|source venv/bin/activate|

3. Install dependencies from venv with `pip install notebook` or `pip install jupyterlab`
4. Run notebook with `jupyter notebook`

## Installing ipywidgets
1. Ensure that node version is 16.x
2. In jupyter env, type `jupyter labextension install @jupyter-widgets/jupyterlab-manager`
3. Import in notebook
