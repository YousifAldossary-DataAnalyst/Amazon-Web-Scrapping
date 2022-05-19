# Amazon-Web-Scrapping

### Summery
Test a new method of data analytics, where I found the idea online to do analysis on live data from online web-page sallers in this case Amazon. Here are two files, one where I started working on a T-shirt change of prices, and the other of multiple webpages analytics as to check reviews and change in prices. I check the change of value as it drops to a certain price of a persons liking to get a message or notification as the item is on discount now. The other is to check for review and availablitiy of item or page existance, by doing text analytics based normally on ID or Class to find common words match the review of the product as for 1 star we look for bad, terrible or similar negative words while 5 stars has great price, high quality or other positive words.

### Dependencies
Jupyter: csv, panda, time, requests, datetime, bs4, smtplib

### Object based considerations
  - Attributes and Numerics
    1. Title
    2. Price
    3. Date
  
  - Methods:
     1. Manually find the names of Ids through browser inspect and copy paste page URL.
     2. Create csv with titles, where the data will be stored daily.
     3. build a function for aimed price.
     4. Recieve notification when the website drop the value to the aimed price or lower.
