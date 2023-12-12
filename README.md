# Project_1

## Project Idea

## Data Source

## Group Members

## Project Title
Overview
This project retrieves data from Yahoo Finance and Reddit, performs analysis, and visualizes the relationship between Reddit upvotes and comments. It also fetches historical stock data for a specific symbol from Yahoo Finance and conducts a linear regression analysis.
## Dependencies
* Python 3.x
    * Libraries:
    * json
    * requests
    * praw
    * pandas
    * matplotlib
    * numpy
    * scipy
## Setup
* 		Install the required dependencies using: bash  Copy codepip install json requests praw pandas matplotlib numpy scipy
* 		Replace the placeholder values in the code with your actual API keys, client ID, secret key, Reddit username, and password.
* 		Run the Python script (Reddit_data_pull2.ipynb) in your preferred environment.
## Code Structure
* Section 1: Fetches real-time stock data from Yahoo Finance using RapidAPI.
* Section 2: Retrieves access token from Reddit API for authentication.
* Section 3: Gathers posts from the "wallstreetbets" subreddit related to Tesla, storing relevant information in a DataFrame.
* Section 4: Calculates the mean upvotes from the obtained Reddit posts.
* Section 5: Fetches historical stock data for the last 100 days.
* Section 6: Processes and visualizes the historical stock data using pandas and matplotlib.
* Section 7: Performs linear regression analysis on Reddit upvotes and comments.
## Result
The script outputs visualizations depicting the relationship between Reddit upvotes and comments, as well as historical stock data for the specified symbol.
License
This project is licensed under the MIT License.
## Acknowledgments
* Data sourced from Yahoo Finance and Reddit.
* Special thanks to the developers of the used libraries and APIs.

