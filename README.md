# Webscraping
Webscraping is a process of collecting structured web data in an automated fashion.It is also call web data extraction.Some of the main use cases of web scraping include price monitoring,price intelligence,news monitoring,lead generation and market research among many others.

**Steps For Webscraping**

1)Identify the target website.

2)Collect URLS of the pages where you want to extract data from or parse HTML data.

3)Make request to these URLS to get the HTML of the page.

4)Use locators to find the data in HTML.

5)Save the data in a JSON or CSV file or some other structured format or Transform data into required format.

**Why this Project?**

This project of web scraping helps to extract the data from an Indian e-commerce company named Flipkart where I have extracted the data of televisions(TV) which include the brand, price, specification, ratings of the TV.The motive of building this project was I wanted to buy a TV having higher configuration and I was not able to select the best from these many options. So, this project would help a lot of people like me who are confused in finding the best among many options, not only from Flipkart but also from other websites.      

**Flipkart Webscraping Using Python**

In this project I have used python programming language to scrape the web data as it contains some useful libraries which helps us to extract the data from webpages like beautifulsoup this library helps us to read the webpage or parse the HTML file then a requests library allows us to send request to the HTTP by which we can access the data then a smtplib library, helps us to send mail to any internet machine this library helped me to notify the best TV I could buy and fits in my budget too.And the next one was the DateTime library as the name says it gives the date and time when the data was collected. And the last library named Pandas which helped to create a csv file of the data extracted from the webpage.  

**Technology Used**

I have used Python for this project the reason behind using this programming language is it has inbuilt libraries which helped me to extract the data from Flipkart.

***IDE USED***

Google Colab, a web IDE for python, to enable Machine Learning with storage on the cloud — this internal tool had a pretty quiet public release in late 2017, and is set to make a huge difference in the world of machine learning, artificial intelligence and data science work.

***libraries used***

1.**BeautifulSoup**

Beautiful Soup is a Python package for parsing HTML and XML documents. It creates a parse tree for parsed pages that can be used to extract data from HTML, which is useful for web scraping.

2.**Requests**

Requests will allow you to send HTTP/1.1 requests using Python. With it, you can add content like headers, form data, multipart files, and parameters via simple Python libraries. It also allows you to access the response data of Python in the same way.

3.**smtplib**

The smtplib module defines an SMTP client session object that can be used to send mail to any internet machine with an SMTP or ESMTP listener daemon.

4.**DateTime**

The datetime module supplies classes for manipulating dates and times.

5.**Pandas**

Pandas is an open source library in Python. It provides ready to use high-performance data structures and data analysis tools.Pandas module runs on top of NumPy and it is popularly used for data science and data analytics.DataFrame is the key data structure in Pandas. It allows us to store and manipulate tabular data as a 2-D data structure.Pandas provides a rich feature-set on the DataFrame. For example, data alignment, data statistics, slicing, grouping, merging, concatenating data, etc.
