# My First Serverless API

My first serverless REST API built during School of Code and deployed to AWS

## Dependencies:

- serverless (creates the serverless API)
- aws-sdk (allows the API to be deployed to AWS using S3 buckets and Lambda functions)
- dynamoDB (links with AWS DynamoDB)
- uuid (creates long random ids for each new bootcamper created)

## To run:

- After any changes, run serverless deploy in the terminal; this redeploys it to AWS with the changes.

## Endpoints:

- Get the list of bootcampers (GET): https://g4ufkuumw7.execute-api.eu-west-1.amazonaws.com/dev/bootcampers
- Get a specific bootcamper (GET): https://g4ufkuumw7.execute-api.eu-west-1.amazonaws.com/dev/bootcampers/{id}
- Add a bootcamper (POST): https://g4ufkuumw7.execute-api.eu-west-1.amazonaws.com/dev/bootcampers
- Update a bootcamper (PUT): https://g4ufkuumw7.execute-api.eu-west-1.amazonaws.com/dev/bootcampers/{id}
- Delete a bootcamper (DELETE): https://g4ufkuumw7.execute-api.eu-west-1.amazonaws.com/dev/bootcampers/{id}
