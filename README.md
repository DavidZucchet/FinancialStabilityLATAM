# Financial Stability LATAM Project

# Table of Contents
1. Installation
2. Project Motivation
3. File Descriptions
4. Results
5. Licensing, Authors, and Acknowledgements

# Installation
There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python. The code should run with no issues using Python versions 3.*.

# Project Motivation
For this project, I was interested in using the data provided by the WorldBank to build a Webpage where I can search for the principal economic and financial variables regarding the bank sector (Capital Robustness, liquidity, margin loan deposits and non performanced loans) in LATAM and monitor its behaviour, as well to apply software engineering skills as web deployment in HTML, CSS, Javascript languages and the usage of Python libraries as Bootstrap, Flask and gunicorn.

# File Descriptions
There are 2 folders containing the scripts for wrangling the data, and the web application.

The scripts folder contains 1 python file that has the code for extracting the data from the WorldBank API and transform it into plotly figures that will be visualize in the HTML page.

The worldbankapp folder contains two python files: "__init__.py" and routes.py. THe first one calls the flask app for deploying the web and the latter requests the images and load it into the web page. 

Finally the file named "worldbank.py" in the main folder intiailize the process for deplying the web and calls the files. There is a requirements file and runtime for keeping storage the version of Python and the libraries in order to replicate the application in another enviroment.x<>

Comments were used to assist in walking through the thought process for individual steps.

# Results

### Instructions:

1. Run the following command in the app's directory to run your web app.
    `gunicorn worldbank.app`

3. Go to http://127.0.0.1:8000/

The dynamic graphs can be found at the web app.

# Licensing, Authors, Acknowledgements
Must give credit to Udacity for the learning path in the DataScientist Course and some of the code that I reused. Otherwise, feel free to use the code here as you would like!




