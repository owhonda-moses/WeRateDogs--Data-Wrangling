# DATA WRANGLING
## INTRODUCTION

> I wrangled data from WeRateDogs, a Twitter account with the handle, @dogrates. This Twitter account rates people’s dogs with humorous comments about the dogs with most dogs scoring 10/10 or higher because _‘they are good dogs…’_
This steps taken in gathering, assessing, cleaning and storing the data are documented.

### GATHERING

In this step, three pieces of data were gathered and represented as pandas DataFrames.
- The first piece of data, provided by Udacity, was a Twitter archive of WeRateDogs in CSV format, and this file was manually downloaded as _‘twitter-archive-enhanced.csv’._
- The second piece of data was a TSV file containing tweet image predictions which was programmatically downloaded from a provided URL as _‘image-predictions.tsv’._
- The last piece of data was a JSON data of the archived tweets, which was pulled from Twitter API using Twitter's access library, tweepy. Each tweet’s data was written to its own line and stored as _‘tweet_json.txt’._

### ASSESSING & CLEANING
Visual and programmatic assessments were done and copies of the dataframes were made. Several content and structural issues were identified and the data was cleaned sequentially, using the define, code and test process, leaving our data trimmed to 1663 tweets with 13 variables.

### EXPLORATORY ANALYSIS
For the analysis, I decided to research the most popular breed of dog and the factors that determine how many retweets and likes a tweet could receive; and so, I set out to address these research questions by gaining more insights into the data.

### KEY FINDINGS
From our insights and visualizations, we deduced that the `Golden Retriever` is the most popular breed of dog and typically, variables such as _dog breed_ and _dog stage_ are determinants of number of likes and/or retweets.

### STORAGE
The cleaned master DataFrame was saved in a CSV file as ‘twitter_archive_master.csv’.

#### LIBRARIES USED

- JuPyter notebook
- pandas
- numpy
- matplotlib
- seaborn
- requests
- os
- json

_Notable references for this project include -_
- https://stackoverflow.com/
- https://github.com/
- https://www.geeksforgeeks.org/
- https://pandas.pydata.org/
- https://wiki.python.org/
- https://docs.tweepy.org/
- https://www.w3resource.com/
- https://pythonguides.com/
