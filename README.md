# Serverless Auth0 Template

This serverless template pushes Auth0 authorizer code to an AWS Lambda in a few steps. 

## Setup

* Clone repository
* Install serverless with `npm i -g serverless`
* Install dependencies with `npm install`
* Fill `serverless.yml` file
* Run `npm deploy:pro` to deploy to production

## How can I refer this authorizer from my serverless functions?

Simply put the field 'authorizer' inside an http event with the ARN of this lambda.

## Credits

This project is a fork from [this one from Auth0-Samples](https://github.com/auth0-samples/jwt-rsa-aws-custom-authorizer)