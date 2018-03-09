# Lambda-HTTPS-Posts
Make HTTPS Posts with JSON payloads in AWS Lambda easily (no extra dependencies required) - Uses Python 3.6

**This code works with the following services**
- Twilio (SMS, Notification & Voice services)
- Mailgun (Email services)
- Lifx (lightbulbs)

**This code makes it easier to send POST requests to HTTPS end points.**
It allows you to:
1. Pass authorisation credentials (user/pass)
2. Pass data in JSON format to the REST API
3. Easily combine different parts of information passed in via the 'trigger' that starts the Lambda function into text strings that are passed out in the JSON file to the REST API.


**1. Make sure to set your Code type correctly in Lambda:**

![Code input settings](https://raw.githubusercontent.com/CameronTurner/Lambda-HTTPS-Posts/master/Lambda%20-%20Code%20input%20settings.PNG)


**2. Set your environmental variables to store and pass your user ID and password into the code**

![Environmental variable settings](https://raw.githubusercontent.com/CameronTurner/Lambda-HTTPS-Posts/master/Lambda%20-%20Environmental%20Variables.PNG)

**3. Monitor the Lambda time outs if your API takes a while to respond. Also consider DNS lookups can take longer than expected sometimes**

![Time out settings](https://raw.githubusercontent.com/CameronTurner/Lambda-HTTPS-Posts/master/Lambda%20-%20Test%20timeouts%20with%20large%20data%20sets.PNG)


## Support / Disclaimer:
- This code probably isn't perfect, test it well and do some security checks to get it right.
- If you need help, let me know by posting an issue/commenting and I'll update the guide/code.
