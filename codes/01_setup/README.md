# Download and install Anaconda environment for Python 3.7

https://www.anaconda.com/download/

# Create new anaconda environment for this class
```sh
conda create --name anlp python=3.9.23
 ```

# Activate environment

```sh
source activate anlp
```

# Check version (should be 3.7.1)

```sh
python --version 
```
https://docs.conda.io/projects/conda/en/latest/user-guide/getting-started.html

# Install packages

Be sure to install these specific versions to make debugging easier for everyone in class.

```sh
conda install nb_conda=2.2.1
conda install nltk=3.4
conda install spacy=3.8.7
conda install scikit-learn=1.5.2
conda install pandas=2.1.4
conda install matplotlib=3.8.4
conda install jupyter ipykernel
python -m ipykernel install --user --name anlp --display-name "Python (anlp)"
```

# Install spaCy English model

```sh
python -m spacy download en
```

# Use Jupyter notebooks

That's it! Whenever you're ready to use a Jupyter notebook in this setup, open up the terminal and navigate to the folder containing the notebook; then activate the anlp environment to access these libraries and start up the notebook:

```sh
source activate anlp
jupyter notebook
```

We'll be using Jupyter notebooks extensively in this class; if you're new to them, check out the tutorial here:

* [Jupyter notebook tutorial](https://www.dataquest.io/blog/jupyter-notebook-tutorial/)

If you haven't used Github before, you'll just need it to pull course materials (notebooks, data) from the anlp repo.

* [Install git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
* ` git clone git@github.com:convergedmachine/nlp-grad-source.git`
* Whenever you want to update your local copy: `git pull`

See here for an intro to Git/Github:


* https://product.hubspot.com/blog/git-and-github-tutorial-for-beginners


