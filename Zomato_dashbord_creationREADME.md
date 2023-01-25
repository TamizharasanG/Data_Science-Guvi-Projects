# Guvi_Tasks
ReadMe document for Zomato worldwide data analysis


This Zomato dataset consist of Online delivery orders and Dine In orders of various Countries. The major part of data belongs to various cities in India. 
This project is to create the dashboard for understanding of the sales in each countries with respech to their mode of orders, spending habit of people 
from various countries, and also a detailed comparison between the Indian cities. This dashboard also focus on the favourite dishes of each part  and also 
an business view on each cities and countries on which the famous cuisiens, costly cuisiens, famous restarents, high performing resteraunts, low performing restarents 
etc.., and at the end it also have the graphical representation of country wise analysis of some important features like mode of orders from each countries, 
cost of living of countries, preferred price range of countries.

In the coding part I have attached a Colab notebook where you can explore the.For this project I used various type of packages for various purposes and attached the 
reference below.
![image](https://user-images.githubusercontent.com/119114780/214648442-bdee3890-112f-45ca-9c46-0b8ddcb47df6.png)

In the data the price is given in their regional currency. I have used a package called easy-exchange-rates to convert the value to one common value (Indian currency value) 
INR value and proceeded for the further process. I have made a funnel chart with plotly express where it shows the comparision between the exchange rates of each country
with respect to the INR value
![image](https://user-images.githubusercontent.com/119114780/214648550-8f4b447d-b9d1-49b9-a4ea-bf118686e1cc.png)

I have made this project into two parts in the notebook. In the first part all exploration process,explination for the new packages used are mentioned till end . 
Where as in the second part the same code is executed with some basic exploration and raw code till dashboard development.
After executing all cells from part 1 or part 2 click the link to enter the dashboard.
![image](https://user-images.githubusercontent.com/119114780/214648699-395df596-9305-450c-b960-76c554bb8677.png)

 About the dashboard
![image](https://user-images.githubusercontent.com/119114780/214648766-01e789b9-9bb4-49bf-bfb4-584406ec2239.png)
The first option in our dashboard in a dropdown for selection of the country name. After selection of the country name, you can see the table with favourite cuisine of
the country, total contribution etc…
After that there will be 2 charts available a box plot and a pie charts which describes the spending habit and mode of orders of the selected country.

![image](https://user-images.githubusercontent.com/119114780/214648902-5d5b1f4c-dbb8-413e-8b18-529315405f22.png) 
The next dropdown consist of Indian city names which are listed in the data. After selecting the city you can find a table of data which represent detailed analysis of the faviurite cuisiens, costly cuisiens, high and low revaneu restraunts etc. And belowthat you can find 2 charts box and pie plot which represents the spending habit and mode of preferred order type were shown.
 
![image](https://user-images.githubusercontent.com/119114780/214648947-2bcec712-568b-4ce9-9d40-fbb0681f5ff6.png)
And the next part have 2 selection types one is to select the feature that you want to explore and another one is to select the preferred map type. Here I have used 2 map types choropleth and scatter plot. By selecting that you can find a graphical representation of the countries with some additional information about the countries data

