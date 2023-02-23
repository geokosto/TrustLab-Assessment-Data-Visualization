# TrustLab Data Scientist Technical Assessment - Data Visualization

This project involves data visualization tasks as part of TrustLab's Data Scientist Technical Assessment. The code is written in Python and uses several libraries such as os, wordcloud, plotly, pandas, ipywidgets, and IPython.display. At first, i developed an streamlit app because it's a library i am familiar with. Then i migrate the app into a jupyter notebook. 

## Project overview

The project involves those main tasks:

- Load data, merge them and convert them to a pandas dataframe: The first task involves loading data from a set of JSON files in a specified directory, merging the data from these files into a single dataframe, and then converting this dataframe into a pandas dataframe. The goal of this task is to prepare the data for visualization.

 - Data distribution: The second task is to create a histogram of the distribution of a feature in the dataset. The user can select a feature from a dropdown menu, and then adjust the number of bins for the histogram using a slider. The goal of this task is to provide an interactive visualization that allows the user to explore the distribution of the data.

 - Geographical data: The third task involves creating a map plot that shows the geographic locations of tweets in the dataset. The user can toggle the display of usernames on the map using a checkbox. The goal of this task is to create an interactive visualization that allows the user to explore the geographical distribution of the data.

 - Sentiment Time Series: The fourth task is to create a time series plot of the average sentiment and subjectivity scores over time. The user can explore the trends in sentiment and subjectivity scores by date. The goal of this task is to create an interactive visualization that allows the user to explore the sentiment and subjectivity patterns in the data over time.
 
 - Sentiment Vs Subjectivity: The fifth task is to create a scatter plot that visualizes the relationship between sentiment scores and subjectivity scores. 
  
 - Sentiment Heatmap: The sixth task is to create a heatmap of sentiment scores by day of the week and time of day. The function begins by dropping rows with invalid datetime values in the 'created_at' column and adding columns for day of the week and time of day. It then creates a pivot table with the mean sentiment score for each weekday and hour. 
  
 - Description Wordclouds: The final task is to create a word cloud of the user descriptions in the given data

## Prerequisites

The code requires Python 3 and the following libraries:

    os
    wordcloud
    plotly
    pandas
    ipywidgets
    IPython.display

You can install these libraries using the following command:

```
pip install os wordcloud plotly pandas ipywidgets IPython.display
```

## How to use

To run the project, follow these steps:

- Clone or download the project from the GitHub repository.
-Open the project directory in a Python environment (e.g., Jupyter Notebook or any Python IDE).
- Run the code cells in order.

## Acknowledgments

This project was created as part of the TrustLab Data Scientist Technical Assessment. 
