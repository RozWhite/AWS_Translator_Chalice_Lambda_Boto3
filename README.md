# AWS Translator App with Chalice , Lambda and Boto3<br />

Build and deploy a serverless application with Chalice local  <br />
The process for the image translator will be:
          An image is read from the S3 bucket via a lambda function. 
          In the next step, this image is passed to the Rekognition service via calling rekognition API. 
          In response, rekognition API returns labels. A function reads the labels and calls Amazon Translate. 
          To speak translated text, Amazon Polly is used with Amazon Translate. <br />
