***Geo-Tagged Tweet Analysis and Newsworthiness Scoring***

**Overview**

This project focuses on analyzing a dataset of approximately 10-20K tweets from London/UK, provided in JSON format. The key objectives of this project include spatial analysis of tweets, developing a newsworthiness scoring system, and visualizing the results.

**Project Objectives**

1. Spatial Analysis of Tweets

* Organize tweets into 1km x 1km grid cells based on geographic coordinates.

* Generate statistics and visualizations to analyze data distribution.

* Discuss challenges related to geo-localization of tweets.

2. Newsworthiness Scoring

* Develop a method to classify tweets into high-quality, low-quality, and background tweets.

* Define and adjust thresholds to compute a newsworthiness score.

* Analyze the effect of stopwords, thresholds, and other filtering techniques on tweet classification.

3. Application of Newsworthiness Scoring to Geo-Tagged Data

* Apply the scoring method to the spatially organized tweets.

* Identify tweets with low and high newsworthiness scores, setting a threshold to remove low-scoring tweets.

* Compare filtered vs. unfiltered data and analyze their differences.

4. Discussion on Geo-Localization Issues

* Explore challenges related to geo-localization in social media data.

* Identify common issues with geotagged tweets and propose possible solutions.

**Data Description**

* Dataset Location: JSON files in the Data directory.

* Geographical Bounding Box for London: [-0.563, 51.261318, 0.28036, 51.686031]

* Tweet Attributes: Includes tweet text, timestamp, geolocation data, user information, etc.

**Implementation Steps**

1. Organizing Tweets into 1km x 1km Grids

* Convert latitude/longitude coordinates into a grid-based representation.

* Count the number of tweets per grid cell.

* Generate visualizations to analyze tweet distribution.

2. Newsworthiness Scoring Method

* Develop a scoring algorithm based on the dataset of high/low-quality tweets.

* Experiment with different thresholds and stopword filtering to refine scoring.

* Conduct empirical analysis to justify threshold selection.

3. Applying Scoring to Geo-Tagged Tweets

* Use the computed newsworthiness score to filter tweets.

* Compare statistics before and after filtering.

* Visualize the differences in tweet distribution.
