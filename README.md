# Lab: 12 - Data Analysis with Pandas

## Overview

Today we’re taking a tour into Data Science to learn a bit more about the field and tools used in this space!

The best way to hone your data analysis skills is consistent, deliberate practice. One of the best places to acquire data for analysis is [Kaggle](https://www.kaggle.com/), so practice your abilities with some [Kaggle](https://www.kaggle.com/) data sets.

Sign up for a Kaggle account (if you don’t already have one).

## Feature Tasks and Requirements

- Find and download the following data sets:
  - [Video Game Sales](https://www.kaggle.com/gregorut/videogamesales) - Sales data from more than 16,500 games
  - [Cycle Share Data set](https://www.kaggle.com/pronto/cycle-share-dataset) - Bicycle Trip Data from Seattle’s Cycle Share System
- Start two Jupyter Notebooks called vg-stats and bike-stats
- Add a markdown cell at the top of each notebook with the title of this assignment, an appropriate name for the data set, as well as your name and the date
- Load up each of these data sets into a Pandas DataFrame within each respective file.

- In the `vg-stats` notebook answer the following questions/do the following tasks. Note that the numbers quoted for sales are in the millions, and apply only for those games with over 10,000 sales.:

1. Which company is the most common video game publisher?
2. What’s the most common platform?
3. What about the most common genre?
4. What are the top 20 highest grossing games?
5. For North American video game sales, what’s the median?

- Provide a secondary output showing ten games surrounding the median sales output
  - assume that games with same median value are sorted in descending order

6. For the top-selling game of all time, how many standard deviations above/below the mean are its sales for North America?
7. The Nintendo Wii seems to have outdone itself with games. How does its average number of sales compare with all of the other platforms?
8. Come up with 3 more questions that can be answered with this data set.

- In the `bike-stats` notebook, answer the following questions/do the following tasks:

  1. What is the average trip duration for a borrowed bicycle?
  2. What’s the most common age of a bicycle-sharer?
  3. Given all the weather data here, find the average precipitation per month, and the median precipitation.
  4. What’s the average number of bikes at a given bike station?
  5. When a bike station is modified, is it more likely that it’ll lose bikes or gain bikes? How do you know?
  6. Come up with 3 more questions that can be answered with this data set.

When you’re done answering all of the questions for each data set, clean up your notebooks leaving only cells that contain relevant data and calculations. Then restart and run your notebook so that the cell numbering is sequential from top to bottom

Have fun with the data!! Play around a bit, and see if there’s anything else you can/want to do with the info available!
