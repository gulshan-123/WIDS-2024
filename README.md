# Stocks Uncovered: Web Scraping and Time Series Analysis

## Overview
This project introduces web scraping and time series analysis to gain insights into stock markets. Over four weeks, participants will learn how to collect, clean, and analyze stock data, working up to building a basic predictive model. No prior experience is required; each week builds on foundational concepts.

### Objectives
- **Web Scraping**: Learn techniques to collect stock data from websites.
- **Data Cleaning and Processing**: Organize and clean data for analysis.
- **Time Series Analysis**: Understand trends, seasonality, and apply basic statistical methods.
- **Prediction Models**: Build simple forecasting models to predict stock prices.

---

## Weekly Outline

Here’s the revised **Week 1** schedule with an emphasis on Python basics, Jupyter Notebook, and introductory libraries.

---
Install Python from [Python](https://www.python.org/downloads/)<br>
Download VS Code from [Visual Studio Code](https://code.visualstudio.com/)<br>
Download the Python extension for Visual Studio Code from the Extensions menu on the left side.<br>

### **Week 1: Introduction to Python and Data Tools**
- **Objective**: Get familiar with Python, Jupyter Notebook, and essential data libraries for the project.
- **Topics**:
  - **Python Basics**: Variables, data types, loops, and functions.
  - **Jupyter Notebook**: Setting up and using Jupyter for interactive coding.
  - **NumPy**: Working with arrays and performing basic mathematical operations.
  - **pandas**: DataFrames, data manipulation, and basic operations.
  - **matplotlib**: Plotting and visualizing data.

- **Setting up VS code for jupyter notebook**
Video link: [Jupyter Notebook Setup](https://youtu.be/suAkMeWJ1yE)
Note: You may skip the virtual environment creation, Just click on any python version and thing will run smoothly...

Write `pip install numpy pandas matplotlib` in any terminal to install them.

- **Resources for Python**:<br>
Learn as much as you can! These are required for any Data Science projects. You may refer other resources too.
  - [W3 Schools](https://www.w3schools.com/python/): You may refer W3Schools for numpy pandas and matplotlib too.
  - [Python Official Documentation](https://docs.python.org/3.13/tutorial/index.html)
  - [YouTube python Tutorial](https://youtu.be/kqtD5dpn9C8?si=GkOcxIJrRW_oS-Kd)
  - [NumPy docs](https://numpy.org/doc/2.1/user/absolute_beginners.html)
  - [numpy video](https://www.youtube.com/watch?v=QUT1VHiLmmI)
  - [pandas docs](https://pandas.pydata.org/docs/getting_started/intro_tutorials/index.html)
  - [pandas video](https://www.youtube.com/watch?v=dUpyC40cF6Q&list=PLUaB-1hjhk8GZOuylZqLz-Qt9RIdZZMBE)
  - [matplotlib Tutorial](https://matplotlib.org/stable/tutorials/introductory/pyplot.html)

- **Activities**:
  - **Python Practice**: Basic exercises to practice loops, conditions, and functions.
  - **Jupyter Notebook Setup**: Installing Jupyter and practicing simple notebook commands.
  - **NumPy and pandas**: Creating arrays, loading data into DataFrames, and performing operations.
  - **Visualization**: Creating simple line plots to visualize example datasets.

  Demo: https://github.com/veb-101/Numpy-Pandas-Matplotlib-Tutorial

---

### **Week 2: Introduction to Web Scraping** 
- **Objective**: Grasp web scraping basics and collect data.
- **Topics**:
  - HTML structure, HTTP requests.
  - Using Python libraries like `BeautifulSoup` and `requests`.
- **Resources**:
  - [Intro to Web Scraping with Python](https://realpython.com/beautiful-soup-web-scraper-python/)
  - [BeautifulSoup Documentation](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
  - [Data Cleaning Tutorial](https://realpython.com/python-data-cleaning-numpy-pandas/)
  - Video Resources (any one):
    - [Corey Schafer Selenium and requests 45 min](https://youtu.be/ng2o98k983k)
    - [FreeCodeCamp.org video tutorial for web scraping 1hr](https://youtu.be/XVv6mJpFOb0)
- **Activities**:
  - Explore HTML structure of a stock website (choose a website of your own choice).
  - Write a basic script to scrape stock prices.

  demo: https://github.com/israel-dryer/Yahoo-Finance-Scraper
---

### **Week 3: Introduction to Time Series Analysis**

#### **Objective**
To understand fundamental concepts of time series analysis, including trends and seasonality.

#### **Topics**
- Basics of time series data and its visualization.
- Simple moving averages and trend analysis.

#### **Resources**
- **Primary Resource**: [STAT-510](https://online.stat.psu.edu/stat510/)
  - Read lessons 1, 2, 3, and 4 (theoretical concepts).
- **Python Practicals**:
  - Learn to use ARIMA and SARIMA models from the `statsmodels.tsa` package.
  - [Microsoft Introduction to ML: ARIMA](https://github.com/microsoft/ML-For-Beginners/tree/main/7-TimeSeries/2-ARIMA): Also try to do `assignment.md` given [here](https://github.com/microsoft/ML-For-Beginners/blob/main/7-TimeSeries/2-ARIMA/assignment.md).

> **Note**: The recommended book includes R code examples, which are not essential for this course. Python is sufficient for our purposes. If interested, you may explore additional chapters for further learning.

#### **Demo**
- **Stock-related Time Series Analysis**:
  - [Kaggle Tutorial: Everything You Can Do With a Time Series](https://www.kaggle.com/code/thebrownviking20/everything-you-can-do-with-a-time-series)
    - A comprehensive tutorial, though it may be slightly outdated for local execution. Use the "copy and run" feature on Kaggle for experimentation.
- **General Time Series**:
  - [Kaggle Tutorial: Avocado Price Forecast with ARIMA/SARIMA](https://www.kaggle.com/code/tanmay111999/avocado-price-forecast-arima-sarima-detailed#Time-Series-Analysis)

> **Note**: Focus on ARIMA and SARIMA as foundational tools. For those with a background in Machine Learning or an interest in advanced techniques, consider exploring [Recurrent Neural Networks (RNN)](https://en.wikipedia.org/wiki/Recurrent_neural_network), [NN for forcasting](https://medium.com/microsoftazure/neural-networks-for-forecasting-financial-and-economic-time-series-6aca370ff412).

#### **Activities**
1. **Data Collection**:
   - Scrape stock data from websites.
2. **Visualization**:
   - Plot stock data to identify patterns.
3. **Analysis**:
   - Compute moving averages to smooth trends.


---

### **Week 4: Forecasting and Model Building**
Will be updated later
- **Objective**: Build a basic forecasting model for stock prices.
- **Topics**:
  - Introduction to forecasting methods (e.g., Simple Exponential Smoothing).
  - Evaluating model accuracy.
- **Resources**:
  - [Forecasting Time Series Data](https://www.machinelearningplus.com/time-series/)
  - [Evaluating Model Performance](https://towardsdatascience.com/evaluation-metrics-for-regression-models-75db4a33154b)
- **Activities**:
  - Build a simple forecasting model.
  - Create a final report on the project findings and model predictions.

---

## Project Deliverables
1. **Scripts**: Code for web scraping, data cleaning, and analysis.
2. **Weekly Notes**: Observations and learnings from each week.
3. **Final Report**: Overview of the process, key insights, and model predictions.

Happy Coding!

---