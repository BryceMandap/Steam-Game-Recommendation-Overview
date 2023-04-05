# Steam Game Recommendation Overview
https://public.tableau.com/app/profile/bryce.mandap/viz/SteamGamePublisherRecommendation/Purpose.

## Background
Steam is a digital platform that distributes digital computer games. It currently holds the largest market share of online game sales. Currently Steam lists over 90,000 game titles across its services, with over 25 million concurrent users. Due to the mass amount of differing games titles, publishers, and developers, it can be difficult to enter the market successfully. This company is an up-coming gaming developer that is interested in developing a new game to distribute exclusively on Steam.

## Introduction
A gaming company wants to  start to develop some games, and they know that games with better reviews tend to make more money. While the performance of the game is of course the top priority of the game developers, the company wants to know if there are any other factors that can contribute to higher reviewed games? 

- Questions of General Interest
  - When do games have the highest/lowest ratings? 
  - Which genre is the most valued?
  - Should our game be within a specific length? Do players tend to like longer games? 
  - Are games more enjoyable if it's on mac and windows? Should we convert our games to mac users? Is this worth additional resources? 
  - Does price have a direct relationship with the amount of reviews/rating? 
  
## Data
The available data includes: 
- Game listing data (title, release_date, price, developer, etc).  
- User reviews per game (user_id, rating, review_date, etc)

# Project Breakdown
To help the stakeholder navigate through different analyses, I added rectangular buttons on the top of the page to simulate a task bar.           
 Within each button, you can view 3 different types of analyses. I also added a Conclusion page in the end that summarized significant insights.     
 
 ALL report sections can be filtered by selected the desired Genre on the top-right of the screen.

## 1. Market Overview
 - This page of the report was designed to help the stakeholders be able to quickly identify significant metrics and KPI's
 - It also allowed them to understand where the competitors are placed in the market
    - This was accomplished by creating a bar chart that enabled the user to dynamically alter the Axes based on their desires
       - For instance, it can show the **top publishers** by the **number of games** with an **average rating score of 90%**.
  
![image](https://user-images.githubusercontent.com/129364286/229992177-509a166d-96cb-4cb1-bfe7-82e02d385633.png)

 
## 2. Game Ratings & Release Trends
- The purpose of the section is help analyze significant game attribute trends such as the rating and number of downloads
  - Analyzed Game Rating growth over both month and year by creating a dynamic distribution bar chart
  - Created a dual-axis chart that showed the release growth and their percent differences over 11 years
  
  ![image](https://user-images.githubusercontent.com/129364286/229992232-d8c69cca-b2f3-45f8-ba4c-fbed6dced951.png)


## 3. Price Analysis
- This page was dedicated towards price optimization for their desired games
  -  Developed a price distribution char that showed the frequency of different price points
  -  Showed the average price growth depending on what game genre was selected
  - Compared the top performing game publishers and their price points to see where the price market leaders are currently at. 
  
  
  ![image](https://user-images.githubusercontent.com/129364286/229992322-c59444ff-881d-4163-903b-c8eed84fc3eb.png)

  
## Insights & Suggestions Examples 
**Game Genre Recommendation**

Due to Indie games being low-cost in nature, it is most suitable for your current market position. While the majority of games on Steam are Indie games, there has been a large decrease in releases within the past couple years. This can also be an opportunity to enter the market.

**When to Release**

While the largest amount of high reviews being towards the end of the year, this can be due to the amount of total games during that time. To avoid compeitiors I advise to release the game in Septermeber since this shows the opportunity for growth. The amount of games being released has been significantly decresing since 2018. Strategy, Indie, and Action have the highest amount of decreased releases. This can be a sign of an opening in the market.

**Pricing**
Pricing ultimately comes down to the amount of resources/expenses for the game. However based on trends, pricing the game at $0-4 or $40-44 are both good options since they have high expected sales and high rating score
