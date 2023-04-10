# AWS-Serverless (Please Read)👇
 Serverless Web depoloyment by leveraging AWS services namely AWS Amplify,AWS Cognito,AWS DynamoDB,AWS Lambda,API Gateway


## Deployment in Brief <br>

- Firstly I created a static landing page i.e. index.html which was deployed using <b>AWS Amplify.</b>. 

- Then using <b>Amazon Cognito</b> I made a User pool to store users and to ensure login authenication. I customised the email and password for authenicating them.
  
    <p> After that I integrated the pool-Id and App Client-Id on the config.js to connect the user pool.</p>
  
- Now in order to fulfill user request of a unicorn I made a Lambda function using <b>Amazon Lambda</b> and the requests were stored in a table which I made using the <b>Dynamo DB</b>.

    <p> As mentioned Lambda function (requestUnicorn) in the index.js was used to handle the unicorn requests for users. </p>

- Then using Amazon API I fetched the Lambda Function which enabled users to request a unicorn from wherever they clicked on a map.
    <p> At last I updated the invokeURL on config.js to fetch the function. </p>

### PS: Due to some issue with my aws account I am currently unable to access the AWS resources to render the full website. Presently, only the static landing page is available. So I decided to mention what all I did on the project in this readme. I apologize for the same.</h3> 
