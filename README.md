# Sentiment_Analysis

Dataset from:
https://www.kaggle.com/datafiniti/hotel-reviews/version/1#7282_1.csv
```
sentiment_model = gl.logistic_classifier.create(products,
                                                     target='sentiment',
                                                     features=['word_count'],
                                                     validation_set=test_data,
                                                     max_iterations=15)
```

**[ERROR] graphlab.toolkits._main: Toolkit error: Target column has missing value.                    Please use dropna() to drop rows with missing target values.**


Code from:
https://github.com/YeWang0/Sentiment_Analysis