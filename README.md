# Pandas Expert

[Talk by James Powell](https://www.youtube.com/watch?v=pjq3QOxl9Ok)

Notebook follow along / notes from presentation and code snippets

**NOT** A word for word text transcription

Some examples changed slightly or added in

Formatting varies between James' `print(x,y,z, sep='\n')` format and ipython cell outputs.

Other Recommended James Powell Python talks:

- [So you want to be a Python expert?](https://www.youtube.com/watch?v=cKPlPJyQrt4)
- [Objectionable Content](https://www.youtube.com/watch?v=1SHi1kriJI4)

## Local Setup

Check version is at least Python 3.9 and install all requirements (ignore `venv` bits if you want to install in your current python environment):

```sh
python --version
# 3.10.0
python -m venv venv
. ./venv/bin/activate
python -m pip install -r requirements.txt
```

*note:* If you need assistance with setting up python, [here's my way](https://tech.gerardbentley.com/python/beginner/2022/01/29/install-python.html).
For a guide on using Jupyter Notebooks, [here's one from Real Python](https://realpython.com/jupyter-notebook-introduction/)

Non-`notebook` requirements (if you prefer not to do the scipy or xarray examples):
- `pandas`
- `scipy`
- `xarray`

Launch the notebook (or open in your code editor of choice that supports notebooks):

```sh
python -m jupyter notebook pandas_expert.ipynb
```

(If this fails to launch the notebook direcly, open the URL that should appear in your terminal in a browser then click the `pandas_expert.ipynb` file)
