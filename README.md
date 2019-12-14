# FYS-STK4155 Project 3
This is the source code for our 3rd and final project in the course [FYS-STK4155 Applied Data Analysis and Machine Learning ](https://www.uio.no/studier/emner/matnat/fys/FYS-STK4155/index-eng.html) at the University of Oslo.

This project aims at comparing the classification performance of a Multilayer Perceptron model and an XGBoost model with the much simpler method of k Nearest Neighbours. The data set used can be found [here.](http://archive.ics.uci.edu/ml/datasets/MAGIC+Gamma+Telescope)

The code in this project is relatively short and is therefore contained in a single Jupyter notebook.

Please install dependencies using [Pipenv](https://github.com/pypa/pipenv) by using the command <tt>pipenv install</tt>.

## Source structure 

* <tt> src/main.ipynb</tt>: Main notebook containing all code used.
* <tt> src/data</tt>: Folder containing the data set.
* <tt> src/models </tt>: Folder containing the models. 
* <tt> doc/report_3.pdf</tt>: Project report.
* <tt> doc/report_3.tex</tt>: Report latex file.
* <tt> doc/figures/</tt>: Folder containing all figures generated and used in the report.

We have used [Black](https://github.com/psf/black) for proper code formatting in Python.
