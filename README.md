# [Jupyter notebooks](https://jupyter.org/install.html) for processing data from [42's API](https://api.intra.42.fr/apidoc/)

# Usage 

	brew install python3
	pip3 install -r requirements.txt
	jupyter-notebook

## Why .Rmd?

Jupyter notebooks are nice to look at, but don't play nicely with version control in their native `.ipynb` format.  We're using [Jupytext](https://github.com/mwouts/jupytext) to convert the notebooks to `.Rmd` for use with git.  To version control!
