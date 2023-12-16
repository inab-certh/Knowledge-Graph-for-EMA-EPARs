## Set up
### Step 1: Create a Virtual Environment
```
virtualenv <venv>
```

### Step 2: Activate the new environment
```
source <venv>/bin/activate
```

### Step 3:  Install the requirements
```
pip install -r requirements.txt
```

### Step 4: Add Virtual Environment to Jupyter Notebook
You can add your virtual environment to Jupyter by typing:

```
python -m ipykernel install --user --name=<venv>
```

Now you are able to choose the environment as a kernel in Jupyter Notebook. 
