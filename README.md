# cloudhub-app-info v2
Trying to figure out what apps are deployed across your organization? Ever been asked how many cores each app is using? Do you know what percentage of CPU each app is using?   Well this API can answer all those questions and more for you!


Usage:
This API will not have a security policy applied to it unless you:

- Import all the API assets (RAML, examples, etc) into Design center
- Promote to exchange & pull into API Manager
- Copy the API Id from API Manager and is it for the next step 

The following steps apply whether this API is secured or not:

- update the src/main/resources/mule-dev.yaml properties file
- Deploy to a Mule runtime or launch in Studio
- Use API Console to interact with API & request data
- limit requests to no more than 10 days of data
- results will be emailed to the specified account
