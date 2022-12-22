# Bay Area Bike Share Analysis

## Introduction
This project has two parts that demonstrate the importance and value of data visualization techniques in the data analysis process. In the first part, you will use Python visualization libraries to systematically explore a selected dataset, starting from plots of single variables and building up to plots of multiple variables. In the second part, you will produce a short presentation that illustrates interesting properties, trends, and relationships that you discovered in your selected dataset. The primary method of conveying your findings will be through transforming your exploratory visualizations from the first part into polished, explanatory visualizations.

## Project Overview
This project is divided into two major parts. In the first part, you will conduct an exploratory data analysis on a dataset of your choosing. You will use Python data science and data visualization libraries to explore the dataset’s variables and understand the data’s structure, oddities, patterns and relationships. The analysis in this part should be structured, going from simple univariate relationships up through multivariate relationships, but it does not need to be clean or perfect. There is no one single answer that needs to come out of a given dataset. This part of the project is your opportunity to ask questions of the data and make your own discoveries. It’s important to keep in mind that sometimes exploration can lead to dead ends, and that it can take multiple steps to dig down to what you’re truly looking for.

In the second part, you will take your main findings from your exploration and convey them to others through an explanatory analysis. To this end, you will create a slide deck that leverages polished, explanatory visualizations to communicate your results. This part of the project should make heavy use of the first part of the project.

Dataset Overview:
The dataset has 174952 rows and 17 columns for Ford GoBike System, which covers the greater San Francisco Bay area. The dataset contains:

- trip duration
- start/end time for bike rides
- start date for bike rides
- start/end station names
- customer data

## Summary of Findings

96% of trips were less than 30 minutes and 0.79% of trips were more than an hour, which can be considered as outliers. When looked into duration_sec column most of the values fall below 2000 seconds with the peak between 500-600 seconds. Further most of the riders are the subscribers who represent 90% and are the majority bike riders compared to customers who represent only 9%. On further analysis it is discovered that the number of trips spiked around 7am - 9am and 4pm - 6pm. This might be related to the time when employees and students go to and leave work and school. Further, the analysis is made on the trips over week days where subscribers utilization of serveice is consistent over the week days and decline on weekends. Customers have longer trips on each day of the week compared to subscribers which allows us to consider that subscribers are mostly the employees and students who take the ride to work and school and vice-versa.

## Key Insights for Presentation

Following are the insights for the presentation:
- The duration of the trip are 96% less than 30 minutes.
- Subscribers utilization of serveice is consistent over the week days and declines on weekends.
- Demand for bikes are high during the peak hours (7am - 9am and 4pm - 6pm).
- The Shorter usage of the bike by the subscribers correlate with peak hours, which shows that the use is primarily for work commute or school commute.
- The longer rides taken by the customers show heavy use over weekends and afternoons, might be for city tour or leisure.
