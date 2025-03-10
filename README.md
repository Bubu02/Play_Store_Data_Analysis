#  🧸Playstore Data Analysis📈

This repository contains various analyses and visualizations of Playstore data. Each analysis provides insights into different aspects of the data. Below is a detailed description of the analyses included in this project.

## Table of Contents 🦖
- [Scatter plot for Revenue and Number of Installs](#scatterplot)
- [Reviews Word Cloud](#wordcloud)
- [Sentiment Distribution Barplot](#sentimentcarplot)<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Playstore Data Analysis</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 20px;
            background-color: #f4f4f4;
        }

        h1 {
            text-align: center;
            color: #333;
        }

        ul {
            list-style-type: none;
            padding: 0;
        }

        ul li {
            margin-bottom: 10px;
            position: relative;
            padding-left: 20px; /* Add padding for the dot */
        }

        ul li::before {
            content: "•"; /* Customize this character to your preference */
            position: absolute;
            left: 0;
            color: #333; /* Customize the color of the dot */
            font-size: 1.2em; /* Customize the size of the dot */
        }

        ul li a {
            text-decoration: none;
            color: #333;
            font-weight: bold;
        }

        ul li a:hover {
            color: #ff6347;
        }

        .image-container {
            float: right;
            margin: 0 0 20px 20px;
            width: 700px; /* Adjust the width as needed */
        }

        .image-container img {
            width: 100%;
        }

        .clear {
            clear: both;
        }
    </style>
</head>
<body>
    <h1>🧸Playstore Data Analysis📈</h1>
    <p>This repository contains various analyses and visualizations of Playstore data. Each analysis provides insights into different aspects of the data. Below is a detailed description of the analyses included in this project.</p>

    <h2>Table of Contents 🦖</h2>
    <ul>
        <li><a href="#scatterplot">Scatter plot for Revenue and Number of Installs</a></li>
        <li><a href="#wordcloud">Reviews Word Cloud</a></li>
        <li><a href="#sentimentcarplot">Sentiment Distribution Barplot</a></li>
        <li><a href="#choroplethmap">Choropleth Map for Global Installs</a></li>
        <li><a href="#groupedbarchart">Grouped Bar Chart for Average Rating & Total Review Count</a></li>
        <li><a href="#timeserieschart">Timeseries Chart</a></li>
        <li><a href="#bubbleplot">Bubble Plot</a></li>
    </ul>

    <h3 id="scatterplot">Scatter plot for Revenue and Number of Installs ✨</h3>
    <div class="image-container">
        <img src="https://github.com/user-attachments/assets/7dd3ca7c-028a-46d8-9c5f-a97760a92093" alt="Scatter Plot Image">
    </div>
    <p>This scatter plot shows the relationship between the number of installs (x-axis) and revenue in USD (y-axis) for paid apps across multiple categories. The data points are color-coded by app category, with 20 different categories represented including Business, Communication, Dating, Education, and others. The blue trendline indicates a strong positive correlation between the number of installs and revenue - as installs increase, revenue generally increases as well. The plot shows data points ranging from 0-16 installs and $0-18 in revenue.</p>
    <div class="clear"></div>
    <h4>Some notable observations:</h4>
    <ul>
        <li>Business apps (light green) appear to have some of the highest revenue points</li>
        <li>Communication apps (orange) show strong performance in the higher install ranges</li>
        <li>The data forms a relatively tight band along the trendline, suggesting a consistent relationship</li>
        <li>There's more data density in the middle range (6-14 installs), indicating this might be the typical performance range for paid apps</li>
    </ul>
    
    <h3 id="wordcloud">Reviews Word Cloud 🌦</h3>
    <p>To run the scripts, you need to have Python installed along with the necessary libraries. You can install the required libraries using the following command:</p>
</body>
</html>

- [Choropleth Map for Global Installs](#choroplethmap)
- [Grouped_bar Chart for Average rating & Total Review Count](#groupedbarchart)
- [Timeseries Chart](#timeserieschart)
- [Bubble Plot](#bubbleplot)

## Scatter plot for Revenue and Number of Installs ✨

This scatter plot shows the relationship between the number of installs (x-axis) and revenue in USD (y-axis) for paid apps across multiple categories. The data points are color-coded by app category, with 20 different categories represented including Business, Communication, Dating, Education, and others.
The blue trendline indicates a strong positive correlation between the number of installs and revenue - as installs increase, revenue generally increases as well. The plot shows data points ranging from 0-16 installs and $0-18 in revenue.
<div style="display: flex; justify-content: flex-end;">
    <img src="https://github.com/user-attachments/assets/7dd3ca7c-028a-46d8-9c5f-a97760a92093" alt="Scatter Plot Image" style="width: 150px; margin-left: 20px;">
</div>

### Some notable observations:
- Business apps (light green) appear to have some of the highest revenue points
- Communication apps (orange) show strong performance in the higher install ranges
- The data forms a relatively tight band along the trendline, suggesting a consistent relationship
- There's more data density in the middle range (6-14 installs), indicating this might be the typical performance range for paid apps


## Reviews Word Cloud 🌦
To run the scripts, you need to have Python installed along with the necessary libraries. You can install the required libraries using the following command:
