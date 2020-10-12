# Udacity_DAND_Project4_DataWrangling

**Goal:** 
Wrangle WeRateDogs Twitter data to create interesting and trustworthy analyses and visualizations of the dog rating twitter feed. 

Enhance the twitter data with information of likely breed of the dog being rated based on images available in the tweets.

To achieve this, create a solid and clean master dataset. Based on the analysis of this create two reports. 


**Data sourced:**
- WeRateDogs Twitter archive - twitter-archive-enhanced.csv
- Neural Network dog preditor data - image-predictions.tsv
- Additional Tweet data (retweet count, favorite count) - access through Twitter API - stored in: twitter_retweet_favorite_count.csv and tweet_json.txt

**Key points:**
- only look at original ratings - no retweets with images
- find 8 quality issues and 2 tidy issues in dataset
- store clean master data in a file called `twitter_archive_master.csv`
- analyse and visualise the data with at least three insights and 1 visualization
- create a 300 - 600 word written report called wrangle_report.pdf that briefly describes your wrangling efforts. This is to be framed as an internal document.
- Create a 250-word-minimum written report called act_report.html that communicates the insights and displays the visualization(s) produced from your wrangled data. This is to be framed as an external document, like a blog post or magazine article, for example.
- data limited until 1st Aug 2017

**Documents created during the project:

Masterdocument:
    project4_twitter_data_wrangling_and_analysis.ipynb
Clean Masterdatafile:
    twitter_archive_master.csv
Reports:
    wrangle_report.ipynb
    wrangle_report.pdf
    act_report.ipynb
    act_report.html
   
Graphs:
    monthly_mean_rating.png
    most_common.png


**Set up:**

Python libraries needed:

Pandas
NumPy
requests
tweepy
json
cfg
os
Path 
load_dotenv
matplotlib.pyplot

Twitter API: Twitter developer account needed.

**Contributions:**
This is a project that is being submitted to Udacity and this version is the final revision