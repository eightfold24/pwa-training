# Ditch the server with AWS

Serverless is the native architecture of the cloud that allows you to build and run applications and services without thinking about servers. It eliminates infrastructure management tasks such as server or cluster provisioning, patching, operating system maintenance, and capacity provisioning.

There are a number of different providers of serverless capabilities such as...

* Azure Functions
* Google Cloud
* IBM Cloud Functions

But in this tutorial we are going to use Amazon's AWS to give our website a backend datastore.

## Prerequisites
For this part of the tutorial we assumes you have a website with a form that is ready to submit some data to a datastore.  You will also need access to the following.

- An AWS account*
- A text editor
- Recommended browser: The latest version of Chrome

_*There are login credentials stored in the private Applied Innovation Sharepoint page, under [accounts](https://kainossoftwareltd.sharepoint.com/sites/appliedinnovation/Lists/Accounts/AllItems.aspx). Use the "AWS - User Access" account._

## TODO

This tutorial is broken up into five modules. You must complete each module before proceeding to the next.  

1. [AWS Introduction](01-Intro)
2. [Creating a Serverless Backend](02-Serverless-Backend)
3. [Exposing our RESTful API](03-RESTfulAPI)
4. [Hosting a Static Website](04-Static-Website)
5. [Cleaning Up](05-Cleanup)

***Content from this document is adapted from https://aws.amazon.com/getting-started/projects/build-serverless-web-app-lambda-apigateway-s3-dynamodb-cognito/***