# Project-2
There are three sources of dataset for the analysis of WeRateDogs datasets, which are listed and explaine
below:
1. twitter-archive-enhanced.csv: This archive is in csv file format and contains basic tweet data (tweet ID,
timestamp, text, etc.) for all 5000+ of their tweets as they stood on August 1, 2017. This was
downloaded from thier twitter archive for the purpose of this project and read into the dataframe.
2. image-predictions.tsv: This contains table full of image predictions alongside each tweet ID, image
URL, and the image number that corresponded to the most confident prediction (numbered 1 to 4
since tweets can have up to four images). This is hosted on Udacity's servers, it is in tsv file format and
was downloaded programmatically using the
Requests library.
3. tweet-json.txt: This is the resulting data from twitter_api.py. This was read read line by line into
DataFrame with (at minimum) tweet ID, retweet count, and favorite count.
