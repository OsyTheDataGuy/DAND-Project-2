# WeRateDogs : A Data Wrangling Project
## by Nonso Udechukwu


## Introduction

This data wrangling project is the second project of the ALX-T Data Analyst Nanodegree programme on Udacity. The project focused on wrangling and analysing data from @WeRateDogs Twitter account.

This involved:
   - gathering data from multiple sources (downloaded @WeRateDogs' Twitter archive dataset and image predictions data using the Requests library, and queried Twitter API using tweepy for additional data),
   - assessing data (visually and programmatically),
   - cleaning and merging the datasets, and then
   - performing analysis on the tweets to extract insights.

## Libraries Used
- Pandas: For storing and manipulating structured data.
- Numpy: For multi-dimensional array, matrix data structures and, performing mathematical operations
- Matplotlib: For all visualizations (including maps and graphs)
- Seaborn: a Python data visualization library based on matplotlib. It provides a high-level interface for drawing attractive and informative statistical graphics.
- tweepy: open-sourced, easy-to-use for accessing the Twitter API. It gives you an interface to access the API from your Python application.
- requests: allows you to send HTTP requests using Python.
- os: For interacting with the operating system
- json: For parsing JSON into a Python dictionary or list. It can also convert Python dictionaries or lists into JSON strings.
- re: provides a set of powerful regular expression facilities, which allows one to quickly check whether a given string matches a given pattern (using the match function), or contains such a pattern (using the search function).

## Project Methodology
The main steps for this project are as follows:

- Data Wrangling:
  - Data Gathering
  - Data Assessment
  - Data Cleaning
- Analysis and Visualisation
- Conclusions/Results

## Key Insights
Based on the data and analysis carried out, I found that:

1. There's a very positive correlation (r=0.93) between retweets and favourite count of a tweet.
2. Tweets of the doggo-puppo category overwhelmingly outperformed the rest in retweets and likes. @WeRateDogs might focus on this category for future tweets, given its apparent popularity with the followers.
3. Tweeting from a web browser seems to have gathered more retweets on average. It is important to note that other factors (such as tweet content) are likely contributing here.

## Limitations
1. 84% (1561/1851) of the dogs didn't have a category. This means conclusions about dog stage were made on a very small portion of the observations.

2. A tweet source "Vine - Make a Scene" wasn't part of the final analysis. I suspect this tweet source was dropped when I dropped retweet rows and tweets with nonstandard dog names.

3. I couldn't query additional data on 29 tweets. 28 of the tweets threw up "No status found with that ID" error, while one threw up "Sorry, you are not authorized to see this status" error.

## References
Below are some of the websites I consulted for this project:

   - Pandas Combine Two Columns of Text in DataFrame, SparkByExamples, <a href="https://sparkbyexamples.com/pandas/pandas-combine-two-columns-of-text-in-dataframe/">Website Link</a>

   - How to Convert Text Data from Requests object to DataFrame, StackOverflow, <a href="https://stackoverflow.com/questions/39213597/convert-text-data-from-requests-object-to-dataframe-with-pandas">Website Link</a>

   - BeautifulSoup: Extract Text from Anchor Tag, StackOverflow, <a href="https://stackoverflow.com/questions/11716380/beautifulsoup-extract-text-from-anchor-tag">Website Link</a>

   - Authenticate the Twitter API with Python (Tweepy), JC Chouinard, <a href="https://www.jcchouinard.com/how-to-use-twitter-api-with-python/">Website Link</a>

   - How to Make a Table in Jupyter Notebook, CodeGrepper, <a href="https://www.codegrepper.com/code-examples/typescript/how+to+make+a+table+in+jupyter+notebook">Website Link</a>

