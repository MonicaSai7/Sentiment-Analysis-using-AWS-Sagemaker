# Sentiment-Analysis-using-AWS-Sagemaker
The notebook and Python files provided here, once completed, result in a simple web app which interacts with a deployed recurrent neural network performing sentiment analysis on movie reviews. This project assumes some familiarity with SageMaker, the mini-project, Sentiment Analysis using XGBoost, should provide enough background.<br/><br/>
The general outline for this SageMaker project using a notebook instance:
  - Download or otherwise retrieve the data.
  - Process / Prepare the data.
  - Upload the processed data to S3.
  - Train a chosen model.
  - Test the trained model (typically using a batch transform job).
  - Deploy the trained model.
  - Use the deployed model.<br/><br/>
In this project testing the model is carried out by deploying the model and then using the deployed model by sending the test data to it. One of the reasons for doing this is so that you can make sure that your deployed model is working correctly before moving forward.<br/>
### The Sample Web App Output
![web-app-output](./Web%20App%20Output.png)

