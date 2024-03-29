# Module 1. Overview

In this tutorial, you'll create a simple serverless web application that posts the form information to a datastore and returns some response with data.

## Application Architecture

The application architecture uses [AWS Lambda](https://aws.amazon.com/lambda/), [Amazon API Gateway](https://aws.amazon.com/apigateway/), [Amazon S3](https://aws.amazon.com/s3/), [Amazon DynamoDB](https://aws.amazon.com/dynamodb/), and [Amazon Cognito](https://aws.amazon.com/cognito/) as pictured below:

![Serverless Component Arcitecture](https://d1.awsstatic.com/Test%20Images/Kate%20Test%20Images/Serverless_Web_App_LP_assets-16.7cbed9781201a79b9efa761807c4312e68b23485.png)

1. **Static Web Hosting**
    
    Amazon S3 hosts static web resources including HTML, CSS, JavaScript, and image files which are loaded in the user's browser.  

2. **User Management**
    
    Amazon Cognito provides user management and authentication functions to secure the backend API. Note that this tutorial does not make use of this section.

3. **Serverless Backend**
    
    Amazon DynamoDB provides a persistence layer where data can be stored by the API's Lambda function.  

4. **RESTful API**
    
    JavaScript executed in the browser sends and receives data from a public backend API built using Lambda and API Gateway.  
    
## First Steps

### Select a Region
The system we are going to launch can be deployed in any AWS region that supports all the services used in this application, which include AWS Lambda, Amazon API Gateway, Amazon S3 and Amazon DynamoDB.

You can refer to the [region table](https://aws.amazon.com/about-aws/global-infrastructure/regional-product-services/) to see which regions have the supported services. Among the supported regions you can choose are:

- US East (N. Virginia)
- US East (Ohio)
- US West (Oregon)
- EU (Frankfurt)
- EU (Ireland)
- EU (London)
- Asia Pacific (Tokyo)
- Asia Pacific (Seoul)
- Asia Pacific (Sydney)
- Asia Pacific (Mumbai)
 
Select your region from the dropdown in the upper right corner of the AWS Management Console.

![](https://d1.awsstatic.com/Getting%20Started/learning-paths/serverless%20web%20application/region.69a7598862b05a8d166ac34108eb6f25f5a90844.png)

### [Next Section >>>](../02-Serverless-Backend)