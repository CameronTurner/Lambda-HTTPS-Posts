# Lambda-HTTPS-Posts
Make HTTPS Posts with JSON payloads in AWS Lambda easily (no extra dependencies required) - Uses Python 3.6

This code makes it easier to send POST requests to HTTPS end points.
It allows you to:
1. Pass authorisation credentials (user/pass)
2. Pass data in JSON format to the REST API
3. Easily combine different parts of information passed in via the 'trigger' that starts the Lambda function into text strings that are passed out in the JSON file to the REST API.


Make sure to set your Environmental variables correctly in Lambda:

![Code input settings](https://raw.githubusercontent.com/CameronTurner/Lambda-HTTPS-Posts/master/Lambda%20-%20Code%20input%20settings.PNG)
