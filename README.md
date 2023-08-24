# Sentiment-Analysis-On-Amazon-Reviews
## purpose
A machine learning model was designed and trained using [Amazon Reviews](https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Watches_v1_00.tsv.gz) to analyze the sentiments of users' comments. </br>
The texts in the dataset were preprocessed, incorporating techniques such as tokenization, the removal of stopwords, lemmatization, stemming, and normalization.</br>
The classification task was performed using Naive Bayes algorithm.

## Description
The dataset was divided into train, test, and validation sections, with proportions of 60%, 20%, and 20%, respectively. </br>
The model's performance was evaluated on the data, and evaluation metrics including accuracy, precision, recall, and F1 score were calculated.</br>
Finally, the predicted labels (positive or negative) for the comments were displayed. </br>
A neural network for sentiment analysis was created using TensorFlow. The dataset used in this project is sourced from the Amazon Reviews for watches. Prior to training the model, the data is preprocessed using techniques such as tokenization, the removal of stopwords, lemmatization, stemming, and normalization.</br>
Furthermore, vectorization methods such as TF-IDF were applied to convert the dataset records into numerical vectors. </br>
To enhance the performance of the neural network, transfer learning was utilized, leveraging the pre-trained language model BERT. Embedded layers were incorporated to capture meaningful representations of the text.

## Team Members
[Hosna Habibi](https://github.com/HosnawHb) </br>
[Pooya Kavosh](https://github.com/Jarvis017) </br>
[Kimia DarvishNoori](https://github.com/KimiaDN) </br>

Please refer to the code in the repository for a step-by-step guide on implementing the neural network, training the model, and evaluating its performance.




