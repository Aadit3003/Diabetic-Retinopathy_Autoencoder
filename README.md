# Autoencoder-based Feature Selection for Diabetic Retinopathy Risk Factors
This project was done under the guidance of Dr Sundaresan Raman, BITS Pilani, as part of the course CS F376 (Design Oriented Project) in the Second Semester of AY 21-22.

## Brief Description
We implemented a Naive Bayes (NB) Sentiment Classifier for Short-form text messages (Tweets), to classify them into binary (mutually exclusive) categories: Positive or Negative.

## Description

- <em><b>Dataset</b></em>: 
- <em><b>Preprocessing</b></em>: 
- <em><b>Training</b></em>:
- <em><b>Visualization</b></em>: 
- <em><b>Results</b></em>:

<img src="https://github.com/Aadit3003/Twitter-Sentiment-Polarity-Analysis/blob/5031f72d5cc1560be4edc5947e48a8733c06bda9/Assets/Sentiment%20140%20Dataset.png"><br>
<em><b>Sentiment140 Dataset, from Kaggle</b></em>

<img src="https://github.com/Aadit3003/Twitter-Sentiment-Polarity-Analysis/blob/5031f72d5cc1560be4edc5947e48a8733c06bda9/Assets/3D%20Embedding%20TSNE.png">
<em><b>TSNE Visualization in 3D Space</b></em>



## Installation and Use

A prediction tool was built using the aforementioned Naive Bayes Classifier. It takes a user tweet as input and then predicts the tweet to have either Positive sentiment, or negative sentiment. The simple python GUI also offers choice of Naive Bayes model (Multinomial or Bernoulli), and whether the user wants to apply feature selection (Chi-Square feature selection or None at all). Some sample results are shown below:

<img src="https://github.com/Aadit3003/Twitter-Sentiment-Polarity-Analysis/blob/cf1829c9a60dac7fe07baebb32fae004e26d4d07/Assets/Positive%20Tweet.png" width = "512"><br>
<em><b>Positive Tweet</b></em><br>

<img src="https://github.com/Aadit3003/Twitter-Sentiment-Polarity-Analysis/blob/cf1829c9a60dac7fe07baebb32fae004e26d4d07/Assets/Negative%20Tweet.png" width = "512"><br>
<em><b>Negative Tweet</b></em>

## References
- <em>Khalid, S., Prieto-Alhambra, D. Machine Learning for Feature Selection and Cluster Analysis in Drug Utilisation Research. Curr Epidemiol Rep 6, 364–372 (2019).</em> ([Paper Link](https://rdcu.be/cQnva))
- Please refer to the PPTs for a more detailed analysis of the three Feature Selection methods and their results.
  - ([PPT 1: Feature Selection (3 methods)](https://github.com/Aadit3003/Diabetic-Retinopathy_Autoencoder/blob/8fd10b7258584e88716d1c40f8f6009797779586/Assets/PPT%20I%20Feature%20Selection.pdf))
  - ([PPT 2: Autoencoder for Feature Selection](https://github.com/Aadit3003/Diabetic-Retinopathy_Autoencoder/blob/8fd10b7258584e88716d1c40f8f6009797779586/Assets/PPT%20II%20Autoencoder.pdf))
