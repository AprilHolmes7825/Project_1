## Project Title: Reddit and Yahoo Finance Data Analysis

## Overview
This project retrieves data from Yahoo Finance and Reddit, performs analysis, and visualizes the relationship between Reddit upvotes and comments. It also fetches historical stock data for a specific symbol from Yahoo Finance and conducts a linear regression analysis.

This project involves the analysis of data from the WallStreetBets subreddit on Reddit and financial data from Yahoo Finance, focusing on Tesla, Inc. The goal is to explore potential correlations between Reddit post engagement (upvotes and comments) and stock market performance.

## Data Source

* Reddit_data_pull.ipynb: Jupyter Notebook containing the Python code for data collection, analysis, and visualization.
* README.md: Documentation providing an overview of the project, instructions, and insights.

## Create a config.py file and set the following variables:
* reddit_client_id = "YOUR_REDDIT_CLIENT_ID"
* reddit_secret_key = "YOUR_REDDIT_SECRET_KEY"
* reddit_user_name = "YOUR_REDDIT_USERNAME"
* reddit_password = "YOUR_REDDIT_PASSWORD"
* yahoo_api_key = "YOUR_YAHOO_API_KEY"

## Data Collection

* Reddit Data
Used the Reddit API and the PRAW library to collect information from the "wallstreetbets" subreddit.
Extracted details such as post title, upvotes, comments, and date.
* Yahoo Finance Data
Utilized the Yahoo Finance API to gather real-time and historical data for Tesla, Inc.
Retrieved information like stock symbol, market price, day range, and historical stock prices.

## Obtain API keys:
Reddit: Create a Reddit app [here](https://www.reddit.com/prefs/apps) to get your client ID and secret.
Yahoo Finance: Get your API key from the [RapidAPI Yahoo Finance API](https://rapidapi.com/apidojo/api/yahoo-finance1).

## Dependencies
* Python 3.x
    * Libraries:
    * json
    * requests
    * praw (Python Reddit API Wrapper)
    * pandas
    * matplotlib
    * numpy
    * scipy
      

## Setup
* 		Install the required dependencies using: bash  Copy codepip install json requests praw pandas matplotlib numpy scipy
* 		Replace the placeholder values in the code with your actual API keys, client ID, secret key, Reddit username, and password.
* 		Run the Python script (Reddit_data_pull2.ipynb) in your preferred environment.

## Usage
* Run the script.
* Enter the stock symbol when prompted.
* Additional search terms can be added for Reddit searches. Press Enter when done.


## Data Analysis

## Reddit Data
Calculated the mean of upvotes for the latest 100 Reddit posts.
Conducted a linear regression analysis on upvotes vs. comments to explore their relationship.

## Yahoo Finance Data
Extracted key financial indicators for Tesla, Inc., such as market price, 52-week range, and average analyst rating.
Obtained historical stock price data for the past 100 days.

# Correlation Analysis

## Merged Reddit and Yahoo Finance data for combined analysis.
Explored potential correlations between Reddit engagement metrics (upvotes and comments) and stock performance.

## Visualization

Created visualizations using Matplotlib to display relationships between Reddit engagement metrics and stock performance.
Plotted linear regression lines to highlight trends.

## Conclusion

* Reddit Engagement vs. Stock Performance: Analyzed the relationship between Reddit post engagement and Tesla stock performance. The linear regression analysis suggests a positive correlation between upvotes and comments, indicating higher engagement for certain stock-related posts.
* Historical Stock Performance: Explored historical stock prices for Tesla, Inc. over the past 100 days. Visualized trends and patterns in the stock's performance.

## Suggestions for Further Analysis

* Sentiment Analysis: Incorporate sentiment analysis on Reddit comments to understand the overall sentiment of the community towards specific stocks.
* Volume Analysis: Explore the correlation between stock trading volume and Reddit engagement to identify potential trends or anomalies.

## Instructions for Running the Code

Ensure all dependencies are installed (pip install praw pandas matplotlib requests).
Run the Jupyter Notebook (reddit_yahoo_analysis.ipynb) to execute the code cells sequentially.

## Result
The script outputs visualizations depicting the relationship between Reddit upvotes and comments, as well as historical stock data for the specified symbol.

## Group Members
1.Lee,Ian
2.Christopher Avallon
3.April Holmes
4.Dave Burgman
5.Navdeep Kaur
## Acknowledgments
* Data sourced from Yahoo Finance and Reddit.
* Special thanks to the developers of the used libraries and APIs.

