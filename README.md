# Amazon-Reviews-Sentiment-Analysis-Deep-RNN
Doing sentiment analysis on Amazon Reviews with Deep Recurrent Neural Networks (RNN)

This code makes use of the data set from this URL:
http://jmcauley.ucsd.edu/data/amazon/

Data set used is that of Amazon Instant Video (37126 reviews)

# Note before execution
This notebook's code actually runs only on a subset of whole data (1280 reviews) for the purpose of quick validation.

If we need to run it for full data set, we should change the code that looks like 
  `reviewsjson_part = reviewsjson[:1280]`
to
  `reviewsjson_part = reviewsjson`

While doing so, the `epoch` hyper parameter should also be adjusted accordingly, to for ex: 10. The other parameters such as batch size, lstm size, and embedding matrix size can also be adjusted.
