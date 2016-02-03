# EC3389 - Big Data
Files for the course taught at Boston College, Spring 2016

## Requirements

Students are required to install the following:
<ul>
<li>Anaconda for Python 3.4 or higher: https://www.continuum.io/downloads [i.e. NOT version 2.7]
<li>Jupyter Notebook (a.k.a. IPython Notebook): http://jupyter.readthedocs.org/en/latest/install.html#new-to-python-and-jupyter
<li>R or RStudio: https://cran.r-project.org/bin/ 


The installation process is straightforward, usually taking about 15 minutes. If you have any major issues, let me know at baisihad@bc.edu.

If you correctly installed 1 and 2, you should be able to open a Notebook by going to your Terminal (Mac) or Prompt (Windows) and typing "ipython notebook" or "jupyter notebook". You should also be able to open and run the ".ipynb" files above. 


## FAQ

<b> I've got Anaconda setup with Python 2.7, can I have both 2.7 and 3.5 at the same time?

Yes.

> conda create -n python3 python=3.5 anaconda
This should install Python 3.5 in a separate environment. To activate it:

> source activate python3
This temporarily modifies the PATH so your computer thinks you only have Python 3. Now, if you type 

> ipython notebook
then you should be able to create a Python 3 Notebook, too. Once you're done, you can simply type

> source deactivate
and you're back to Python 2, just as you were before.


<b> I've got Anaconda setup with Python 3.5, can I have both 2.7 and 3.5 at the same time?

Same deal as above.

