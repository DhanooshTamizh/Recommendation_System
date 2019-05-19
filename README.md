# Recommendation System - Categorize User Interests From Twitter Data
Strategic Marketing Based on User's Interests From Twitter Data

About the Project:
------------------------

This project is to design a recommendation model that helps organization identify their target audience based on users interests and promote special orders and ads thereby enhancing the organizations marketing strategies. It is done by extracting data from Twitter and utilizing the captured data by processing it in order to make an analysis on users interests by using language processing and n grams for categorization of data. The data of users interests are collected from twitter in the form of tweets, retweets and favorites. The
aim of this project to make a research in the field of natural language processing and n-grams in order to find and implement an
effective marketing strategy by measuring real-time tweets and retweets made by user on any topic based on that. In collecting the data, we used tweepy API to extract tweets, retweets and favorites. In continuation to that the twitter entries were classified into relevant categories with an accuracy of 85% by using natural language processing algorithms where an investigation was made on developing a method to analyze positive sentiments of tweets, retweets and favorites resulting in a satisfying 90.45% accuracy for this mining application. The interests of a individual user are depicted in the form of pie chart using matplotlib and overall user interests are depicted in the form of bar graph using bokeh. The methods used in this project can be used for any twitter user account with public opinions.

Steps to run the notebook file:
-----------------------------------
Step 1) 
--------
Install tweepy API using the command “pip install tweepy”

Step 2) 
-------
Write the below in a separate notebook in a separate cell
import nltk
nltk.download()

a) By doing this, a pop-up box will be opened. In that pop-up box, go to models menu and search for the identifier “vader_lexicon” , “punkt” , “averaged_perceptron” and click on download.

b) In the corpora section, search for the identifier “stopwords” and click on download.

Step 3) 
--------
Place the excel sheet named ‘Category_List.csv’ in your present working directory where the provided notebook is referred.

Step 4) 
--------
Open the provided notebook file and click on ‘Run All’ option from the ‘Cell’ menu.

Step 5)
-------
An UI dialog box would be opened. In the UI dialog box, click on browse button and
select the file name ‘User_Set_1’ and click on Open.

Step 6) 
--------
Ensure that the path is populated in ‘path of the user file’ field.

Step 7) 
---------
Click on 'Execute' button from the UI and observe the pie charts generated in the notebook file and bar
chart being generated in a separate tab.

Step 8) 
--------
Verify that the file named ‘Users_Catergory_List.csv’ gets generated that contains the
numbers of users against each category.

Output:
------------
1) Pie-chart of each user depicting their interests can be visualised.
2) Bar-chart comparing the percentage of users against different interest categories can be visualised.
