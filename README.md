# DAND-Wrangling-of-Twitter-Data
This project documents steps taken to wrangle data regarding Twitter user @dog_rates, also known as [WeRateDogs](https://twitter.com/dog_rates). It also documents insights/visualisations drawn from analyzing the wrangled data. To date, @dog_rates has over 6 million followers.

## Datasets
Three datasets were wrangled, and used in the analysis:
1. WeRateDogs tweet archive. Contains 2,356 observations of basic tweet data (tweet ID, timestamp, text etc) prior to August 1, 2017.
2. Tweet JSON scrapped using tweety API. Contains 2,356 observations of additional tweet info (favorite tweet, number of retweets etc).
3. Dog image predictions from a convolutional neural network. Contains 2,075 predictions of dog breed, based on dog images in WeRateDogs tweet archive.
