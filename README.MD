# Indoor positioning using Wifi Fingerprinting

## General

This repository consists of a single major file: "Report.ipynb", and sever extra ones.\
\
It is a Jupyter Notebook, which goes through the prcoess of **attempting to validate** the idea of **using Wifi** signal to create an ***indoor positiong system*** (x, y, z location).

The analyzed data in the project is taken from: http://archive.ics.uci.edu/ml/datasets/UJIIndoorLoc, where further details regarding the dataset and the problem are explained.

### Report.ipynb
The notebook itself describes the problem further, and goes through several iterations of the same problem, each time attempting to improve a single, specific aspect and analyzing the change in the output received to continously improve the output.

It can be viewed as is on GitHub, as the outputs are already rendered.

To run all of it on your local environmnet you'd need to have the following installed:
1. Jupyter Notebook (or Jupyter Lab)
2. The following public packages: Pandas, Numpy, Plotnine, Sklearn.
3. "working_funcs" module (see below)

### working_funcs.py
A module titled "working_funcs.py" is provided, in which a few functions used in the notebook (two permutations on rotating coordinates, and two permutations on normalizing a Series as a percentage of the maximum value in the Series).

To install it, download the folder, navigate to it using the terminal and run:

python3 setup.py install

### UJIndoorLoc.zip
The datasets as downloaded from http://archive.ics.uci.edu/ml/datasets/UJIIndoorLoc
