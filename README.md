# My Programming for Data Analytics Assignments Repository

**By Sharon Curley (G00438863@atu.ie)**

<p align="center">
    <img width="612" height="408" src="./images/image_02.png" alt="Sublime's custom image"/>
</p>

![Image from Mercy University](./images/image_02.png)

###### [Image from Mercy University](https://www.mercy.edu/sites/default/files/styles/1600x700/public/2020-07/iStock-1150199386.jpg?h=6510ad6e&itok=kyPCa_AE)

This repository contains my assignments submission for the module Programming for Data Analytics.
My github repository link is as follows:

[SBCURLEY/pfda-assignments](https://github.com/SBCURLEY/pfda-assignments/tree/main)

## Installation
I had to install the below to get started on this repository
- Python 
- Visual Studio Code
- Cmder
- Jupyter notebook
- github

## Usage
Once the above is installed is complete, you can run the notebooks

## Dependencies
The following libraries are required to execute my notebook:
- `matplotlib.pyplot`: Essential for creating static, animated, and interactive visualizations in Python. It is closely integrated with NumPy and provides a MATLAB-like interface for creating plots and visualizations.
- `numpy`: It contains functionality for multidimensional arrays, high-level mathematical functions such as linear algebra operations.
- `pandas`: Fundamental data analysis and manipulation library built on top of the Python programming language. It offers data structures and operations for manipulating numerical tables and time series.
- `seaborn`: Seaborn is a Python data visualization library based on matplotlib. It provides a high-level interface for drawing attractive and informative statistical graphics.
- `datetime`: The datetime is a built-in module that provides classes for manipulating dates and times.
- `re` This module is used to perform pattern matching and substitution on strings with regular expressions.

Using python, import the following as per notebook

`import matplotlib.pyplot as plt`

`import numpy as np`

`import pandas as pd`

`import seaborn as sns`

`import datetime`

`import re`

## Repository Structure

*1. images*

   This folder contains all the images used in the Project, README & Assignments.

*2. gitignore*

   This gitignore file specifies intentionally untracked files that Git should ignore.

*3. README*

   This file serves as the first point of contact for users and developers who want to understand the purpose, setup, and usage of my repository.

*4. assignment2-weather.ipynb*
   
   This notebook has a plot of the temperature over time with a min and max

   The assignment is divided into the following sections
   - Import Libraries
   - Load the Data
   - Explore the data before plotting
   - Plot the data
   - References

*5. assignment03-pie.ipynb*
   
   This notebook contains a pie chart of peoples email domains in a csv file from a specific url. 

   The assignment is divided into the following sections
   - Import Libraries
   - Load the Data
   - Explore the data before plotting
   - Prepare the data
   - Plot the data
   - References

*6. assignment_5_risk.ipynb*
   
   This program simulates 1000 individual battle rounds in Risk (3 attacker vs 2 defender) and plots the result.

   The assignment is divided into the following sections
    - Import Libraries
    - Rules of Risk
    - The Game
    - Plot the Results
    - References

*7. assignment_6_Weather .ipynb*

   This notebook uses Knock weather data to create useful plots from data sets. 

   The assignment is divided into the following sections
    - About the Assignment
    - Import Libraries
    - Load Data
    - Analysis:This notebook plots the following from a weather data link:
      - The temperature
      - The mean temperature each day
      - The mean temperature for each month
      - The windspeed (there is data missing from this column)
      - The rolling windspeed (say over 24 hours)
      - The max windspeed for each day
      - The monthly mean of the daily max windspeeds (yer I am being nasty here)


## References 

#### Please note References are shared with each assignment notebook for context. 

- Matplotlib Line Charts – Learn all you need to know   https://datagy.io/matplotlib-line-charts/#:~:text=Matplotlib%20makes%20it%20incredibly%20easy%20to%20add%20a%20simple%20line
- pandas.to_datetime   https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.to_datetime.html
- pandas.to_datetime   https://www.geeksforgeeks.org/python-pandas-to_datetime/
- Date tick locators and formatters   https://matplotlib.org/stable/gallery/ticks/date_formatters_locators.html
- w3schools - Python Datetime   https://www.w3schools.com/python/python_datetime.asp#:~:text=Creating%20Date%20Objects.%20To%20create%20a%20date,%20we%20can%20use
- Auto Date Locator   https://matplotlib.org/stable/api/dates_api.html#matplotlib.dates.AutoDateLocator
- Automatically Annotate The Maximum Value In A Plot Created Using The Python Matplotlib library.    https://medium.com/@mdnu08/automatically-annotate-the-maximum-value-in-a-plot-created-using-the-python-matplotlib-library-54c43001e39c#:~:text=We%20can%20then%20annotate%20the%20maximum%20value%20in%20the%20plot
- How to automatically annotate maximum value in pyplot   https://boldena.com/article/7391
- Pandas DataFrame idxmax() Method   https://www.w3schools.com/python/pandas/ref_df_idxmax.asp#:~:text=idxmax()%20method%20returns%20a%20Series%20with%20the%20index%20of%20the
- Customizing annotation arrows   https://matplotlib.org/stable/users/explain/text/annotations.html#customizing-annotation-arrows
- 'pandas.Dataframe.plot.pie' - pie creation  https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.plot.pie.html
- 'How to Matplotlib' - Changing colours and exploding the pie  https://how2matplotlib.com/matplotlib-pie-chart-from-dataframe.html
- 'Matplotlib' - Labeling a pie and a donut   https://matplotlib.org/stable/gallery/pie_and_polar_charts/pie_and_donut_labels.html
- 'pandas.pydata' - Visualisation of a pie plot   https://pandas.pydata.org/pandas-docs/stable/user_guide/visualization.html
- 'w3schools' - Start Angle / Exploding / Shadow    https://www.w3schools.com/python/matplotlib_pie_charts.asp
- 'how2matplotlib.com' - specify the position of the legend relative to the pie chart   https://how2matplotlib.com/bbox_to_anchor.html
- 'Stackoverflow' - How do I use matplotlib autopct?   https://stackoverflow.com/questions/6170246/how-do-i-use-matplotlib-autopct
- Topic 5 Lecture Notebooks - Numpy and Random
- Code Review-Stack Exchange - code without random - https://codereview.stackexchange.com/questions/249260/python-risk-game
- numpy.random.randint - https://numpy.org/doc/stable/reference/random/generated/numpy.random.randint.html 
- Python, numpy sort array - Reverse = True - https://stackoverflow.com/questions/14875248/python-numpy-sort-array
- w3schools - NumPy Sorting Arrays - https://www.w3schools.com/python/numpy/numpy_array_sort.asp
- Efficiently sorting a numpy array in descending order - https://stackoverflow.com/questions/26984414/efficiently-sorting-a-numpy-array-in-descending-order - 
Note to myself: attacker[::-1].sort() sorts the array in place, whereas a=np.sort(attacker)[::-1] creates a new array.    
- The Python Coding Book - Using Python’s NumPy To Improve Your Board Game Strategy: Your Odds When Attacking in ‘Risk’ - https://thepythoncodingbook.com/2022/12/30/using-python-numpy-to-improve-board-game-strategy-risk/
- numpy.append - https://numpy.org/doc/stable/reference/generated/numpy.append.html
- np.append() - How To Use NumPy Append in Python - https://www.nickmccullum.com/numpy-np-append/
- Python's min() and max(): Find Smallest and Largest Values -  https://realpython.com/python-min-and-max/
- Grouped bar chart with labels - https://matplotlib.org/stable/gallery/lines_bars_and_markers/barchart.html#sphx-glr-gallery-lines-bars-and-markers-barchart-py
- Bar Plots in Matplotlib - https://python-fiddle.com/tutorials/matplotlib-bar-plot   x - width/2
- matplotlib.axes.Axes.set_xticks - https://matplotlib.org/stable/api/_as_gen/matplotlib.axes.Axes.set_xticks.html
- Topic 6 Lecture videos and notebook - L1-introduction_datetime.ipynb & L2-Timeseries in pandas.ipynb 
- L3-creating data.ipynb
- Python Doc: Datetime – Basic date & time types       https://docs.python.org/3/library/datetime.html
- w3schools Python Date    https://www.w3schools.com/python/python_datetime.asp
- Real Python: Using Python datetime to Work With Dates and Times     https://realpython.com/python-datetime/
- Python Tutorial.net: Python datetime     https://www.pythontutorial.net/python-standard-library/python-datetime/
- Dataquest: Python Datetime Tutorial: Manipulate Times, Dates, and Time Spans     https://www.dataquest.io/blog/python-datetime-tutorial/
- Datagy: DateTime in Pandas and Python     https://datagy.io/pandas-datetime/
- Python Doc: Datetime – pandas.to_datetime       https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.to_datetime.html
- Geeks For Geeks: Python | Pandas.to_datetime()       https://www.geeksforgeeks.org/python-pandas-to_datetime/
- w3schools Pandas DataFrame loc Property      https://www.w3schools.com/python/pandas/ref_df_loc.asp
- Geeks For Geeks: Python | Pandas DataFrame.set_index()       https://www.geeksforgeeks.org/python-pandas-dataframe-set_index/
- Real Python: Slicing and Dicing With .loc[]      https://realpython.com/lessons/slicing-and-dicing-with-loc/
- Pandas Pydata: Datetime – pandas.DataFrame.resample     https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.resample.html
- SlingAcademy: Basic Resampling: Aggregating Daily to Monthly Data     https://www.slingacademy.com/article/pandas-using-dataframe-resample-method-with-examples/?utm_content=cmp-true
- Scaler.com: Resampling, Rolling Calculations, and Differencing in Pandas     https://www.scaler.com/topics/pandas/resampling-in-pandas/
- Turbolab:Data Cleaning using Regular Expression    https://turbolab.in/data-cleaning-using-regular-expression/
- Geeks For Geeks: Replace values in Pandas dataframe using regex   https://www.geeksforgeeks.org/replace-values-in-pandas-dataframe-using-regex/
- Datagy: Pandas dropna(): Drop Missing Records and Columns in DataFrames      https://datagy.io/pandas-dropna/
- SlingAcademy: Using DataFrame.dropna() method in Pandas     https://www.slingacademy.com/article/using-dataframe-dropna-method-in-pandas/
- Pandas Pydata: pandas.Series.str.strip       https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.Series.str.strip.html
- Geeks For Geeks: Python | Python | Pandas Series.str.strip(), lstrip() and rstrip()      https://www.geeksforgeeks.org/python-pandas-series-str-strip-lstrip-and-rstrip/ 
- w3schools: Pandas cleaning empty cells  https://www.w3schools.com/python/pandas/pandas_cleaning_empty_cells.asp
- Machine Learning Tutorials: pandas to_numeric Tutorial (With Examples)       https://machinelearningtutorials.org/pandas-to_numeric-tutorial-with-examples/
- Pandas Pydata: pandas.to_numeric     https://pandas.pydata.org/pandas-docs/version/2.0/reference/api/pandas.to_numeric.html
- Stack Overflow: Pandas to_numeric       https://stackoverflow.com/questions/69746592/pandas-to-numeric
- Progamiz: Pandas rolling()        https://www.programiz.com/python-programming/pandas/methods/rolling
- Pandas Pydata: pandas.core.resample.Resampler.max          https://pandas.pydata.org/docs/reference/api/pandas.core.resample.Resampler.max.html
- Real Python: Visualizing Data in Python With Seaborn    https://realpython.com/python-seaborn/
- Datagy: Seaborn in Python for Data Visualization   https://datagy.io/python-seaborn/
- Seaborn: Choosing color palettes     https://seaborn.pydata.org/tutorial/color_palettes.html
- Image Airelogic.com/data-and-analytics (https://www.airelogic.com/data-and-analytics)
- Image Mercy University (https://www.mercy.edu/sites/default/files/styles/1600x700/public/2020-07/iStock-1150199386.jpg?h=6510ad6e&itok=kyPCa_AE)


## About Author
- Sharon Curley
  
    My role is a Business Systems Analyst for [Meissner Corporation](https://www.meissner.com/) - a manufacturing company in Castlebar, Co. Mayo. The systems I am supporting currently are Microsoft Dynamics 365 (ERP) for all Meissner entities (Ireland, US, Switzerland, Germany & Italy). I initially started out in functional areas - Customer Service & Supply Chain as I was lucky to be one of the first crew members on board in this company in 2020. I have moved into the IT Dept since March 2023. I have a background in SAP - projects & support, so was drawn back into this area when I saw the opportunity arise within Meissner. I have a keen interest in data as when I was a functional user that was the most challenging part of my role - trying to get meaningful data from the systems we use. I have used excel to an advanced level and started with Power BI. I see a lot of opportunities within Meissner to develop in the Data field. I am hoping I will have the skills to do so.

![Meissner](https://www.meissner.com/wp-content/uploads/castlebar-brief-pdf-image.jpg)

- [Git Hub Profile](https://github.com/SBCURLEY "Sharon Curley")

- [Email](mailto:G00438863@atu.ie?subject=Hi "Hi!")
