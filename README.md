# EC3389 - Big Data
Files for the course taught at Boston College, Spring 2016

# Calendar

Last Updated: Feb 8th, 2016

| Command | Description |
| --- | --- |
| Jan 20th (Wed)  | First day of classes and Homework 0 (math review) handed out |
| Jan 25th (Mon)  | Homework 0 (math review) due |
| Feb 9th (Tue)  | Homework 1 due |
| Feb 29th (Mon) | Homework 2 due |
| Mar 16th (Wed) | Homework 3 due |
| Mar 30th (Wed) | Homework 4 due and MIDTERM |


# Getting Started

Students are required to install the following:
<ul>
<li>Anaconda for Python 3.4 or higher: https://www.continuum.io/downloads [i.e. NOT version 2.7]
<li>Jupyter Notebook (a.k.a. IPython Notebook): http://jupyter.readthedocs.org/en/latest/install.html#new-to-python-and-jupyter
<li>R or RStudio: https://cran.r-project.org/bin/ 
</ul>

The installation process is straightforward, usually taking about 15 minutes. If you have any major issues, let me know at baisihad@bc.edu.

If you correctly installed 1 and 2, you should be able to open a Notebook by going to your Terminal (Mac) or Prompt (Windows) and typing "ipython notebook" or "jupyter notebook". You should also be able to open and run the ".ipynb" files above. 


# FAQ

<b>Q: How should I submit the homeworks?</b> 

Homeworks usually contain a programming section and a theoretical section. The programming section should be submitted in .ipynb form to baisihad@bc.edu by 8h30AM on their due date. The theoretical section should be submitted in person, at the beginning of class on the due date. Theoretical answers can be written by hand (if legible), or typed in a word processor or yet (and preferrably) in Latex compiled to a PDF.


<b>Q: I've got Anaconda setup with Python 2.7, can I have both 2.7 and 3.5 at the same time?</b>

Yes, you can install Python 3.5 in a separate environment. To do so, go to your Terminal or Prompt and type

```
conda create -n python3 python=3.5 anaconda
```
To activate Python 3.5, type

```
source activate python3
```
This temporarily modifies the PATH so your computer thinks you only have Python 3. Now, if you type 

```
ipython notebook
```
then you should be able to create a Python 3 Notebook, too. Once you're done, you can simply type

```
source deactivate
```
and you're back to Python 2, just as you were before.


<b>Q: I've got Anaconda setup with Python 3.5, can I have both 2.7 and 3.5 at the same time?</b>

Same deal as above, but with the version names reversed.
```
conda create -n python2 python=2.7 anaconda
source activate python2
```




