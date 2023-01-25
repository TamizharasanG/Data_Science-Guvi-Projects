# Guvi_Tasks
This is a readMe file for the twitter scrap GUI creation Project
Twitter scraping GUI

This is a Web scrapping GUI with no use of API key. Using the GUI you can scrap unlimited tweets from twitter, limit the counts, and also can set time interval.
This GUI basically works under python code with the use of snscrape module which is used to get the unlimited tweets from the twitter without any API key.
With small introduction to the GUI as follow
![image](https://user-images.githubusercontent.com/119114780/214495964-ac270faa-2066-4820-ab6d-59280786db74.png)

 
This is the interface for the GUI and it has multiple options for hashtags, starting date, ending date and the limit count.
![image](https://user-images.githubusercontent.com/119114780/214496021-f19e747b-7327-4b43-aaf6-da476c6e576d.png)

 
Text box for entering the hashtag or keyword need to be searched

![image](https://user-images.githubusercontent.com/119114780/214496044-8b349d9e-41de-41ca-8086-9c0f0dce3f5f.png)
![image](https://user-images.githubusercontent.com/119114780/214496056-b87ad78a-d02a-4169-aaa6-7412bc4913df.png)
 
Date selector for setting the start date and end date for the effective search.

![image](https://user-images.githubusercontent.com/119114780/214496121-7192fcb8-edea-4a71-847f-19b098f5c58d.png)

This button is used to view the scrapped data as a table in the GUI


![image](https://user-images.githubusercontent.com/119114780/214496149-13038105-5fdf-45f3-a1f8-ea6b73668402.png)
By clicking this button the scrapped content from the Twitter can be downloaded as a csv file to the local device
By clicking this button the scrapped content from the Twitter can be downloaded as a csv file to the local device

![image](https://user-images.githubusercontent.com/119114780/214496235-85812efa-385b-4417-9293-a79e33f6da27.png)
By clicking this button the scraped tweets were uploaded to the Mongo DB database for the storage

This is a simple GUI which is capable of scraping millions of tweets with specified topics and with the specified time range. This twitter data is very much usefull in Data Analysis especially for sentimental analysis of data to get the pulse of the people which is the major goal of many companies nowadays.
I have attached the Github link for notebook that contains the code of the GUI. Few important notices or steps to be followed in the execution of code are as below
•	Since I have done the coding in the Google colaboratory , it is important to connect to the local server(localhost) to the external server .
•	For that tunneling process I have used the module called ngrok which helps us to create a external server link for the internally running streamlit package.

![image](https://user-images.githubusercontent.com/119114780/214496266-8a1811ec-b574-440f-8ba8-dbb6b089bcf1.png)
This  is a file which is created inside the colab which consist of all user defined functions used for scraping,manipulation and updation of data into the database

Step 1 : Execute this cell
![image](https://user-images.githubusercontent.com/119114780/214496359-0419b3e4-cc93-4949-9ae0-e6b80c1788f1.png)

This code consist of the authorization token from ngrk which helps us to tunnel our GUI to the external world. Before starting the code , getting the authorization token from ngrok is mandatory running code in the colab


Step 2 : Second execution.  
![image](https://user-images.githubusercontent.com/119114780/214496405-84194dd7-623a-4ee8-9f23-b0aa905da649.png)

This code is executed to unzip the ngrok essentials in the colab for the tunneling process

Step 3:Third execution.
![image](https://user-images.githubusercontent.com/119114780/214496461-d90e6c70-25c3-4734-83a9-d0b7cd64af06.png)
 
This piece of code will give us the tunneled link where we can use our GUI using the external link . This link will be regenerated whenever this cell is executed.

Step 4: 
![image](https://user-images.githubusercontent.com/119114780/214496500-dad75d42-310f-4d4a-b5f0-8e17d524de44.png)
This cell contails the streamlit GUI codes and is also created as a virtual file inside the colab.

Step 5:
![image](https://user-images.githubusercontent.com/119114780/214496565-8eacb1ed-9b37-4537-a143-036a21b51a7b.png)

This cell executed to run our streamlit app. During execution this will create 2 links . Don’t use that links. They were generated for local purpose and not needed.Just execute this cell and use the above link.

