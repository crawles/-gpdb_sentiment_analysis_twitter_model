## Sentiment Classifer in PL/Python
The `build-sentiment-classifier.ipynb` Jupyter Notebook builds and exports a serialized Twitter sentiment classifier using PL/Python for PostgreSQL, Greenplum Database, or Apache HAWQ.. The classifier is based on the approach of [Go et al](http://cs.stanford.edu/people/alecmgo/papers/TwitterDistantSupervision09.pdf) using the [Sentiment140 data](http://help.sentiment140.com/for-students/). The data can be downloaded from the Sentiment140 website.

The classifier has an accuracy of 80% on the test dataset consisting of several hundred annotated tweets. The training set consists of 1.6 million tweets automatically labeled by assuming that any tweet with positive emoticons, like :), were positive, and tweets with negative emoticons, like :(, were negative. This technique is called distant supervision using emoticons as noisy labels.

## Additional Resources
* [Deploying the model as a service](https://github.com/crawles/text-analytics-service-example)
* [Sentiment analysis on Wikipedia](https://en.wikipedia.org/wiki/Sentiment_analysis)

## Author
`Chris Rawles`
