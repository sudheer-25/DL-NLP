# Sentiment Analysis Using simple RNN,CNN, LSTM and GRU

This project is part of the course CS594 DL for NLP at UIC.

## Summary

### Data Processing

* Datasets used for training the model are [Cornel Polarity](http://www.cs.cornell.edu/people/pabo/movie-review-data/) and [Stanford Sentiment Treebank](https://nlp.stanford.edu/sentiment/)

* Cornel reviews are matched with the original rt snippets to get the labels as they maintain the order of the data from Stanford

* Stanford reviews are then matched with the original rt snippets to extract the labels for Stanford reviews and these are used for training the model

### Training

* All the Deep Learning Models are built using keras to classify the reviews and are later hypertuned


## References

1.https://ieeexplore.ieee.org/document/7363395
<br>
2.https://ieeexplore.ieee.org/abstract/document/8971592
<br>
3.https://medium.com/@mrunal68/text-sentiments-classification-with-cnn-and-lstm-f92652bc29fd

