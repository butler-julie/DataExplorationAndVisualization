# DataExplorationAndVisualization
A tutorial on data exploration and visualization creating for the 2024 APS March Meeting.

## Introduction

## Instructions for Running with Google Colab
[Google Colab](https://colab.research.google.com) is a cloud based software which runs Python notebooks. One of the main perks of Google Colab is that many popular Python libraries come pre-installed, so there is not set-up needed. You can run this tutorial on Google Colab by clicking the "Run in Colab" button at the top of the notebook and then clicking "Copy to Drive" on the toolbar of the Colab window which will open. This will give yoou a copy of the notebook in your Google Drive account which will save any changes you make. If you do not click "Copy to Drive" you will be running the code in a "playground" version of Google Colab which will allow you to change and run the notebook but will not save your changes.



## Instructions for Running Locally
To run this tutorial locally, you must have Python3 installed along with the following packages:

* Jupyter Notebooks
* Numpy
* Pandas
* Matplotlib
* Seaborn
* Scikit-Learn

These libraries can be installed via pip, conda, brew, or any other package manager. 

As currently written, the notebook expects the data file (`nuclear_data.tsv`) to be in the same folder as the notebook. The easiest way to accomplish this is to clone this repo to your computer (you can followig [Github's tutorial on cloning](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository)) and run the notebook from that folder. If you want to move the data file to a different directory than the notebook, you will have to adjust code cell 2 to reflect these changes.

Jupyter notebook can be used to run this tutorial. For information on running a notebook with Jupyter, refer to [Jupyter's tutorials](https://docs.jupyter.org/en/latest/).
