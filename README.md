# FastAI Course 2020

## Setup

```console
virtualenv --python=python3.7 env
source env/bin/activate
pip install -r requirements.txt
```

Update the `requirements.txt` file, when you installed a new dependency with `pip`.

    $ pip freeze > requirements.txt


## Start Jupyter (in virtualenv)

    $ PATH=`pwd`:$PATH PYTHONPATH=`pwd` jupyter-notebook --NotebookApp.token='' 

If you run the notebook on a server, use
    $ PYTHONPATH=`pwd` jupyter-notebook --NotebookApp.token='' --no-browser --port <port>
