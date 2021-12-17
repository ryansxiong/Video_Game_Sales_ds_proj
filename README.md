# Video Game Sales ds proj

## Codes and Resources Used
* **Python Version**: 3.8
* **Packages**: Pandas, Numpy, Matplotlib
* **Visual Tools**: Tableau, Matplotlib
* **Link to data source**: https://www.kaggle.com/gregorut/videogamesales

## Overview
The purpose for this project is to use exploratory analysis to understand how the data is distributed and to find insights for future decision-making. My analysis for video game sales are from 1980-2020. Below you find the questions that I predicted stake holders will want to know about the data. I also created an easy to use interactive dashboard using tableau.

**Objectives**:
* **Genre**
  * What are the top genres (global)?
  * What are the top genres (region)?
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
* **What are the top genres (global)?**

![Screenshot (30)](https://user-images.githubusercontent.com/91089401/146479116-631238b2-52e0-4893-8a54-a91bb653f548.png)

![Screenshot (29)](https://user-images.githubusercontent.com/91089401/146479087-838422a0-dd9b-41ea-9179-7880bf4ce653.png)

* **What are the top genres (region)?**
 * NA

![Screenshot (39)](https://user-images.githubusercontent.com/91089401/146479757-4c744767-1891-4f27-83d6-ca3e14beecb9.png)

![Screenshot (40)](https://user-images.githubusercontent.com/91089401/146479785-f951e8cf-d5be-4741-9e87-869452133a12.png)

* EU
 
 ![Screenshot (38)](https://user-images.githubusercontent.com/91089401/146479849-a9e5601c-e680-41e5-a265-42e14b23be87.png)
 
 ![Screenshot (37)](https://user-images.githubusercontent.com/91089401/146479822-fcd67674-dc30-4a6a-8430-201897a65b48.png)

* JP

![Screenshot (36)](https://user-images.githubusercontent.com/91089401/146479882-c58ca7ea-ef71-4091-b235-f859c65f05c0.png)

![Screenshot (35)](https://user-images.githubusercontent.com/91089401/146479897-08d521a5-3ab3-4e68-97fa-efdad41564e3.png)

_________________________________________________________________________________________________________________________________________________________________________________
* **What are the top 5 games (name) for each genre?**
 
 * Action

![Screenshot (46)](https://user-images.githubusercontent.com/91089401/146483774-cdd521c0-deb1-4c42-b08e-1f05a8a014c9.png)

![Screenshot (48)](https://user-images.githubusercontent.com/91089401/146483761-b18c9eff-38d1-42a7-9118-c79f4844eb15.png)

 * Sports

![Screenshot (49)](https://user-images.githubusercontent.com/91089401/146484132-46e65ee0-a914-445c-bc14-87629435fb15.png)

![Screenshot (50)](https://user-images.githubusercontent.com/91089401/146484148-740f9629-91b6-40eb-b872-558fc5e9e575.png)

* Misc

![Screenshot (51)](https://user-images.githubusercontent.com/91089401/146484295-e8597474-59a7-4852-ab4b-8cc40e0284b3.png)

![Screenshot (52)](https://user-images.githubusercontent.com/91089401/146484304-a84c5d34-9e0a-40a7-820d-7aaee57ef2fe.png)

* Role-Playing

![Screenshot (53)](https://user-images.githubusercontent.com/91089401/146484407-6417633b-223b-406d-b0c5-a5e0086db9e0.png)

![Screenshot (54)](https://user-images.githubusercontent.com/91089401/146484412-8655dfbd-f4c3-4d56-ac0f-06d710f8dd9d.png)

* Shooter

![Screenshot (55)](https://user-images.githubusercontent.com/91089401/146484546-e0cdf7b3-f837-4fac-9132-cbbc48f1602f.png)

![Screenshot (56)](https://user-images.githubusercontent.com/91089401/146484558-09abab40-c5e7-4b49-8ab1-6ea6e4dfe60c.png)

* Adventure

![Screenshot (57)](https://user-images.githubusercontent.com/91089401/146484665-71a509ae-8c26-40c6-8f52-4daad62438b7.png)

![Screenshot (58)](https://user-images.githubusercontent.com/91089401/146484675-2015d606-8f62-4cbf-83e4-251fcb961a31.png)

* Racing

![Screenshot (59)](https://user-images.githubusercontent.com/91089401/146484803-dde5f534-982d-4253-9c29-47846da7e31d.png)

![Screenshot (60)](https://user-images.githubusercontent.com/91089401/146484812-2d0f8595-29ae-4b47-86ec-46bbc1f45d63.png)

* Platform

![Screenshot (61)](https://user-images.githubusercontent.com/91089401/146484897-d1946aac-845b-4850-bf12-4d0bf370154f.png)

![Screenshot (62)](https://user-images.githubusercontent.com/91089401/146484909-5381c7a7-000b-4480-9223-99c01ca5a6ad.png)

* Simulation

![Screenshot (63)](https://user-images.githubusercontent.com/91089401/146485029-eb906f69-ea4e-43a2-9fd3-c534b7781ca9.png)

![Screenshot (64)](https://user-images.githubusercontent.com/91089401/146485044-a3018f55-c935-4487-a315-cee7e1f8d4ef.png)

* Fighting

![Screenshot (67)](https://user-images.githubusercontent.com/91089401/146485655-97f15c2d-f3f3-437b-8a15-641124271776.png)

![Screenshot (68)](https://user-images.githubusercontent.com/91089401/146485674-8be969fb-81f0-4a48-b21c-45a3a358f3eb.png)

* Strategy

![Screenshot (69)](https://user-images.githubusercontent.com/91089401/146485780-51329655-59a5-4cb0-b0b8-4be8fb7238b4.png)

![Screenshot (70)](https://user-images.githubusercontent.com/91089401/146485790-258639e9-9dd2-4146-9f86-521b2160ba23.png)

* Puzzle

![Screenshot (71)](https://user-images.githubusercontent.com/91089401/146485934-91e91b89-3014-4b3a-b929-21e8e51ab6b4.png)

![Screenshot (72)](https://user-images.githubusercontent.com/91089401/146485948-e32c4d59-1de4-4a50-bf61-a1e1510e8661.png)
_________________________________________________________________________________________________________________________________________________________________________________
* **What is the top genre for each year?**
(top genre count)

![Screenshot (74)](https://user-images.githubusercontent.com/91089401/146489261-7787b6c7-96ef-4ec4-91eb-6a436b694960.png)

![Screenshot (76)](https://user-images.githubusercontent.com/91089401/146490108-202c8bf2-417a-4a62-917a-edb397cea5fa.png)
_________________________________________________________________________________________________________________________________________________________________________________
* **What is the highest selling game for each year?**

![Screenshot (75)](https://user-images.githubusercontent.com/91089401/146490129-26b4c6bd-818f-40a8-b9ce-dea1ad6edf54.png)

