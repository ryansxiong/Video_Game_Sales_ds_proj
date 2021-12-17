# Video Game Sales ds proj

## Codes and Resources Used
* **Python Version**: 3.8
* **Packages**: Pandas, Numpy, Matplotlib
* **Visual Tools**: Tableau, Matplotlib
* **Link to data source**: https://www.kaggle.com/gregorut/videogamesales

## Overview
My analysis for video game sales from 1980-2020. Below you find the questions that I predicted stake holders will want to know about the data. I also created an interactive dashboard using tableau.

**Objectives**:
* **Genre**
  * What are the top 5 genres (global)?
  * What are the top 5 genres (region)?
  * What are the top 5 games (name) for each genre?
  * What is the top genre for each year? 
* **Sales**
  * What is the highest selling game for each year?
  * What is the highest selling game (global)?
  * What is the highest selling game for each (region)?
* **Consoles(platform)**
  * What is the top selling console (global)?
  * What are the top selling consoles for every year?
  * What are the top consoles for each (region)?
* **Publisher**
  * Which publishers make the most games?
  * Which publishers made the most revenue?

## Data Cleaning
After downloading the data, I cleaned and manipulated the data for analysis. I made the following changes:

* Dropped "Rank" column
* Used the groupby function to make a new tables for analysis:
  * Top Genres Global
  * Top Genres per region (NA, EU, JP, Other)
  * Top genre per year
  * Top games per genre
  * Top game per year
  * Overal sales over time
  * Top consoles 
  * Top consoles per region
  * Top publishers (count)
  * Top publishers (sales)

## EDA
