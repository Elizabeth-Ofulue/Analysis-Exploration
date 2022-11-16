
## Overview

Real-world data rarely comes clean. Using Python and its libraries, data will be gathered from a variety of sources and in a variety of formats to assess its quality and tidiness, then clean it. This is called data wrangling.

The dataset to be wrangled, analyzed and visualized is the tweet archive of Twitter user @dog_rates, also known as WeRateDogs. WeRateDogs is a Twitter account with over 4 million followers that rates people's dogs with a humorous comment about the dog.

## Data Gathering
The WeRateDogs Twitter archive contains basic tweet data for all 5000+ of their tweets, but not everything. A csv file of the WeRateDogs Twitter archive containing rating, dog name, and dog "stage" that has been exracted programmatically and filtered for tweets with ratings only will be gathered.

A tsv file of the image predictions per dog will also be gathered. This file contains a table full of image predictions (the top three only) alongside each tweet ID, image URL, and the image number that corresponding to the most confident prediction (numbered 1 to 4 since tweets can have up to four images).

Additional data was gathered from Twitter's API to obtain the retweet count and favorite count, these are two notable column omitted from the csv file. Using WeRateDogs Twitter archive and specifically the tweet IDs within it, Twitter's API will be queried and this data will be gathered for all 5000+ tweets.

The objective of this project is to;
* Successfully wrangle, clean and write WeRateDogs Twitter data via the Twitter API to a csv file.
* Combine data from different file formats (csv, txt and tsv)
* Analyze and visualize dog ratings based on the data collected.
