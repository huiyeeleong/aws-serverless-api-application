# aws-serverless-api-application
This is the code repository for AWS Serverless APIs and Apps. It contains all the supporting project files necessary to work through the video course from start to finish.

Serverless computing will shape the future of web development since it allows you to get rid of many issues "traditional" web hosting poses.

Now's the time to dive into this exciting new technology!

Unlike in traditional web hosting, where you spin up servers, configure them and then deploy your code, in serverless applications, you don't manage any servers! Instead, you only provide your code and define when it should get executed. Done!

Without managing any servers, you typically pay way less (since you got no overhead capacity), can react much better to incoming traffic spikes and don't have to worry about server security!

For these very reasons, it's no wonder that serverless computing is on the rise, with more and more companies adopting it!

Below are the service we will be using:
S3 => https://aws.amazon.com/s3/?nc2=h_m1

API Gateway => https://aws.amazon.com/api-gateway/?nc2=h_m1

Lambda => https://aws.amazon.com/lambda/?nc2=h_m1

DynamoDB => https://aws.amazon.com/dynamodb/?nc2=h_m1

Cognito => https://aws.amazon.com/cognito/?nc2=h_m1

Route 53 => https://aws.amazon.com/route53/?nc2=h_m1

CloudFront => https://aws.amazon.com/cloudfront/?nc2=h_m1

<img width="1697" alt="Screen Shot 2021-10-02 at 10 48 30 pm" src="https://user-images.githubusercontent.com/66815986/136188599-f502473c-2f61-46af-a5f2-07177ff1fca4.png">

<img width="1642" alt="Screen Shot 2021-10-03 at 3 32 09 pm" src="https://user-images.githubusercontent.com/66815986/136188622-39b67582-4c07-4cfd-acce-6b4b5f512b82.png">

For the Frontend App which build using angular
You can find the full API documentation here: http://docs.aws.amazon.com/AWSJavaScriptSDK/latest/AWS/CognitoIdentityServiceProvider.html

We used the getUser() method to retrieve a user via access token (which was passed as a query parameter in our setup).

Please run below command to start the angular applications

1. navigate to the compare-yourself folder run:

npm install

2. if issue persist runs

npm install --legacy-peer-deps

3. cd into compare-yourself/src/app and run below command to start the application
npm start
