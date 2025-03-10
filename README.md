#  🧸Playstore Data Analysis📈

This repository contains various analyses and visualizations of Playstore data. Each analysis provides insights into different aspects of the data. Below is a detailed description of the analyses included in this project.

## Table of Contents 🦖
- [Scatter plot for Revenue and Number of Installs](#scatterplot)
- [Reviews Word Cloud](#wordcloud)
- [Sentiment Distribution Barplot](#sentimentcarplot)
- [Choropleth Map for Global Installs](#choroplethmap)
- [Grouped_bar Chart for Average rating & Total Review Count](#groupedbarchart)
- [Timeseries Chart](#timeserieschart)
- [Bubble Plot](#bubbleplot)

## Scatter plot for Revenue and Number of Installs ✨

This scatter plot shows the relationship between the number of installs (x-axis) and revenue in USD (y-axis) for paid apps across multiple categories. The data points are color-coded by app category, with 20 different categories represented including Business, Communication, Dating, Education, and others.
The blue trendline indicates a strong positive correlation between the number of installs and revenue - as installs increase, revenue generally increases as well. The plot shows data points ranging from 0-16 installs and $0-18 in revenue.
<div style="display: flex; justify-content: flex-end;">
    <img src="../Images/task_01.png" alt="Scatter Plot Image" style="width: 150px; margin-left: 20px;">
</div>

### Some notable observations:
- Business apps (light green) appear to have some of the highest revenue points
- Communication apps (orange) show strong performance in the higher install ranges
- The data forms a relatively tight band along the trendline, suggesting a consistent relationship
- There's more data density in the middle range (6-14 installs), indicating this might be the typical performance range for paid apps


## Reviews Word Cloud 🌦
To run the scripts, you need to have Python installed along with the necessary libraries. You can install the required libraries using the following command: