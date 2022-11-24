# AWS Translator App with Chalice , Lambda and Boto3<br />

This project is about building a translator application with AWS Lambda, Chalice and Boto3. Chalice is a framework for writing serverless apps in python. Chalice enables the creation and maintenance of application backends and their deployment on AWS using Amazon API Gateway and AWS Lambda. AWS Lamda is a serverless compute service for run and execute code and only pay per execution. Boto3 is an AWS Sdk for Python for accessing AWS services.

The process for the image translator will be: An image is read from the S3 bucket via a lambda function. In the next step, this image is passed to the Rekognition service via calling rekognition API. In response, rekognition API returns labels. A function reads the labels and calls Amazon Translate. To speak translated text, Amazon Polly is used with Amazon Translate. 
</br></br>

<img src="german.png" class="centerImage" height="400"/>