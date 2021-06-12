# Plagiarism Detection

## Objective

The project's plagiarism detector will examine a text file and perform binary classification; labeling that file as either plagiarized or not, depending on how similar that text file is to a provided source text. 

**Notebook 1: Feature Engineering**

* Clean and pre-process the text data.
* Define features ([containment](https://www.youtube.com/watch?v=FwmT_7fICn0&t=3s) and [longest common sequence](https://www.youtube.com/watch?v=yxXXwBKeYvU&t=2s)) for comparing the similarity of an answer text and a source text, and extract similarity features.
* Select "good" features, by analyzing the correlations between different features.
* Create train/test `.csv` files that hold the relevant features and class labels for train/test data points.

**Notebook 2: Train and Deploy the Model in SageMaker**

* Upload the train/test feature data to S3.
* Define a binary classification model and a training script.
* Train the model and deploy it using SageMaker.
* Evaluate the deployed classifier.
