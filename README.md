# Amazon-Web-Scrapping

### Summery
This me test new method that, where I found the idea online, to do analysis on an exisiting livee data changing. In this situation is the T-shirt once its on sale to a certain value, I would recieve a remind through email, while the code must be running in the background. These kind of live data are great for business analytics. 

### Dependencies
Jupyter: csv, panda, time, requests, datetime, bs4, smtplib

### Object based considerations
  - Attributes
    1. Title
    2. Price
    3. Date
  - Methods:
     1. Manually find the names of Ids through browser inspect.
     2. Create csv with titles, where the data will be stored daily.
     3. build a function for aimed price.
     4. Recieve notification when the website drop the value to the aimed price or lower.
