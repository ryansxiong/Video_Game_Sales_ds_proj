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
* What are the top 5 genres (global)?
![Screenshot (30)](https://user-images.githubusercontent.com/91089401/146479116-631238b2-52e0-4893-8a54-a91bb653f548.png)

![Screenshot (29)](https://user-images.githubusercontent.com/91089401/146479087-838422a0-dd9b-41ea-9179-7880bf4ce653.png)

* What are the top 5 genres (region)?
 * **NA**
![Screenshot (39)](https://user-images.githubusercontent.com/91089401/146479757-4c744767-1891-4f27-83d6-ca3e14beecb9.png)

![Screenshot (40)](https://user-images.githubusercontent.com/91089401/146479785-f951e8cf-d5be-4741-9e87-869452133a12.png)

 * **EU**
 ![Screenshot (38)](https://user-images.githubusercontent.com/91089401/146479849-a9e5601c-e680-41e5-a265-42e14b23be87.png)
 
 ![Screenshot (37)](https://user-images.githubusercontent.com/91089401/146479822-fcd67674-dc30-4a6a-8430-201897a65b48.png)

* **JP**
![Screenshot (36)](https://user-images.githubusercontent.com/91089401/146479882-c58ca7ea-ef71-4091-b235-f859c65f05c0.png)

![Screenshot (35)](https://user-images.githubusercontent.com/91089401/146479897-08d521a5-3ab3-4e68-97fa-efdad41564e3.png)

