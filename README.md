 # Geospatial-Analysis-Zomato
The Zomato dataset analysis aims to understand the factors impacting restaurant establishment in different areas of Bengaluru, helping new restaurants make informed decisions. It also seeks to identify neighborhood similarities based on food preferences in Bengaluru.

![logo](https://upload.wikimedia.org/wikipedia/commons/thumb/b/bd/Zomato_Logo.svg/1200px-Zomato_Logo.svg.png?20220328090416)
# Problem Statement:
Observations on the following are made:
<ul>
  <li>Top restaurant chains in Bangaluru</li>
  <li>How does the price differ between restaurants that accept online orders and those that don't?</li>
  <li>Types of restaurants available</li>
  <li>Top-rated restaurants</li>
   <li> Restaurants located at various locations around Bangalore</li>
  <li>Heatmap of North Indian and South Indian restaurants</li>
  <li>Favorite dishes in various cuisines represented by a word cloud</li>
</ul></p>

# Dataset:
The dataset contains 17 columns as shown below:
<ul>
<li>url - url of the restaurant in the zomato website</li>
<li>address - address of the restaurant in Bengaluru</li>
<li>name - name of the restaurant</li>
<li>online_order - whether online ordering is available in the restaurant or not</li>
<li>book_table - table booking option available or not</li>
<li>rate - overall rating of the restaurant out of 5</li>
<li>votes - total number of rating for the restaurant as of the above mentioned date</li>
<li>phone - phone number of the restaurant</li>
<li>location - neighborhood in which the restaurant is located</li>
<li>rest_type - restaurant type</li>
<li>dish_liked - dishes people liked in the restaurant</li>
<li>cuisines - food styles, separated by comma</li>
<li>approx_cost(for two people) - approximate cost of meal for two people</li>
<li>reviews_list - list of tuples containing reviews for the restaurant</li>
<li>menu_item - list of menus available in the restaurant</li>
<li>listed_in(type) - type of meal</li>
<li>listed_in(city) - neighborhood in which the restaurant is listed</li></ul></p></br>

# Exploratory Data Analysis:
<ul>
  <li>There are different types of charts Bar, Pie, Line, Scatter Plot, Column chart etc. which can visually present the data in a more understandable way.</li>
  <li>Below bar chart shows the most famous restaurant chains in Bangalore with number of outlets.</li></br>
 
<img src="https://github.com/malvika-mall/Geospatial-Analysis-Zomato/blob/main/Visualizations/Most%20Famous%20Restaurant%20Chains.png" alt="Bar Chart">

  <li>The following Stacked bar chart shows the relationship between ratings and online orders accepted by restaurants.</li></br>
  <img src="https://github.com/malvika-mall/Geospatial-Analysis-Zomato/blob/main/Visualizations/Ratings%20Vs%20Online%20Order.png" alt="100% Stacked Bar Chart">
  <li>The below figure represents the bar chart for different types of restaurants.</li></br>
  <img src="https://github.com/malvika-mall/Geospatial-Analysis-Zomato/blob/main/Visualizations/Types%20of%20Restaurants%20in%20Banglore.png" alt="bar cahrt">
  <li>Below scatter plot with X axis denotes the ratings of the restaurants and Y axis denotes the approximate cost for 2 people.</li></br>
  <img src="https://github.com/malvika-mall/Geospatial-Analysis-Zomato/blob/main/Visualizations/Cost%20vs%20Rating.png" alt="scatter plot">
  <li>Word Cloud for Quick Bites Restaurant Type</li></br>
  <img src="https://github.com/malvika-mall/Geospatial-Analysis-Zomato/blob/main/Visualizations/Quickbites%20Restaurant%20WordCloud.png" alt="word cloud">
</ul>

# GeoSpatial Analysis:
## Heatmap of Restaurants in Bengaluru city
<ul>
  <li>For locating the restaurants in geographical map, we need latitudes, longitudes and count of restaurants.</li>
  <li>Extract the "Latitude" and "Longitude" w.r.t. different Locations using Python's Geopy library.</li>
   <li>Generate a "BaseMap" of Bangalore using Python's Folium library.</li>
</ul></br>
!<img src="https://github.com/malvika-mall/Geospatial-Analysis-Zomato/blob/main/Visualizations/194525572-e888e715-84ea-4a83-a304-a2ac19843997.gif" alt="map"></br>

# Conclusions:
<ul>
  <li>Cafe Coffee Day dominates the restaurant chain landscape followed by Onesta and then Empire.</li>
  <li>Online orders are accepted by 64.4% of restaurants, whereas 35.6% of restaurants do not accept them.</li>
  <li>The city of Bangalore is known as a high-tech hub of India, and people who live a busy and modern life are inclined to choose Quick Bites.</li>
  <li>The most common cuisines are North Indian, Chinese, and South Indian. Bangalore is therefore influenced more by the cultures of the north than those of the south.</li>
  <li>Having reviewed the above scatterplot, we can conclude that most of the highest-rated restaurants accept online orders and are budget-friendly as well.</li>
      <li>It is evident that eateries are primarily located in the central Bangalore region. As we get farther from the center of the city, the number of restaurants decreases. Therefore, prospective restaurateurs can consult this to identify suitable places for their business.</li>
</ul>

# Analysis Criteria
* Project folder follows industry standards in terms of structure and naming conventions.
* Analysis has been conducted using Jupyter notebooks and the Anaconda libraries manager.
* Analysis has been conducted using Python and relevant libraries (pandas, NumPy, os, matplotlib, scipy, and seaborn).

**Check out the notebook above to learn more**
