# SageMaker Deployment Project

## Objective

Build a web page which a user can use to enter a movie review. The web page will then send the review off to our deployed model which will predict the sentiment of the entered review.

This involves:
1. Preparing the data by cleaning text, stemming, and tokenizing words
2. Training the neural network with **PyTorch**
3. Deploying the trained model (with model artifacts and inference code) with **SageMaker**
4. Accessing the model endpoint with **AWS Lambda**
5. Triggering the lambda function with **Amazon API Gateway**
6. Interacting with the web application, which contains the public API URL

## Files

* `SageMaker Project.ipynb` - Jupyter Notebook that walks through the entire project.
* `index.html` - HTML file where user submits the review.

## Architecture

<img src=\"Web App Diagram.svg\">
