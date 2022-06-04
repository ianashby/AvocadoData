# Avocados Overview

In this data analysis project, I have utilized a dateset focused on historical data of avocado prices in various regions over many years. The dataset included information on date, average price for the date/region, type (conventional or organic), total volume/sales, and region. [According to the Kaggle source, this data was downloaded from the Hass Avocado Board website in May of 2018 & compiled into a single CSV.](https://www.kaggle.com/datasets/neuromusic/avocado-prices?datasetId=30292&sortBy=voteCount)

The purpose of the this data analysis project is to get a better foundation on using Python libraries such as Pandas and Altair to work with and visualize data. Additionally, as a challenge to myself, I wanted to utilize a basic machine learning model to predict whether an avocado was conventional or organic. At the conclusion of this project, I feel more comfortable finding and analyzing data.

[Software Demo Video](https://youtu.be/dk1kFKhnsxc)

# Data Analysis Results

**What region has the most expensive avocados?**

* Hartford Springfield seems to be the most expensive for conventional and organic avocados with the average price of both combined being over \$3.60 per avocado. San Francisco and New York closely follow. Meanwhile, Houston seems to have the lowest price for both types coming in at about \$2.10.

**What region sells the most avocados?**

* The West and South Central US seem to sell the most volume of Avocados - over 300 million each. What is even more astonishing is the California, a single state compared to whole regions, strongly competes for the second highest volume in avocado sales. Boise and Syracuse are towards the bottom of the list in sale volume.

# Development Environment

Tools:

* VS Code - I utilized VS Code to develop the program.

Language & Libraries:

* Python - Python is a strong programming language for data analysis as it hosts many popular and easy to use libraries such as Pandas and Altair.
    * Pandas - This library makes it easy to read in data into a data frame, as well as provide easy methods to alter and work with the data.
    * Altair - This library makes it easy to plot and visualize the data from Pandas data frames. You can do many different chart types with custom visualizations.

# Useful Websites

{Make a list of websites that you found helpful in this project}
* [Kaggle Avocado Dataset & Examples](https://www.kaggle.com/datasets/neuromusic/avocado-prices?datasetId=30292&sortBy=voteCount)
* [Pandas Youtube Tutorial](https://www.youtube.com/watch?v=vmEHCJofslg)
* [Decision Tree Classifier](https://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeClassifier.html)
* [Altair Docs](https://altair-viz.github.io)

# Future Work

* Go more in-depth with the data. Is there data that needs to be cleaned or adjusted?
* Make region geo-plots that show volume of sales per region on a map - heat map?