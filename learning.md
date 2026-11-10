
I added your project's virtual environment as a Jupyter kernel called "Python (ml venv)". To use it:

- In VS Code or your IDE: click the kernel picker at the top right of lecture1.ipynb, open "Python Environments" (or "Jupyter Kernel…"), and pick Python (ml venv) or ./venv/bin/python.
- In JupyterLab: go to Kernel → Change Kernel… → Python (ml venv). You may need to refresh the page first.

Then restart the kernel and run import pandas as pd again. It should work.

From now on, install packages with venv/bin/pip install <pkg> from the terminal, or run %pip install <pkg> in a notebook cell. %pip always installs into whichever kernel is running.