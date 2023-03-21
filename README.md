# app-runner-simple-web-api-example

## Purpose

To deploy web api server as an App Runner service.
The api is working based on Node.js. 

## How to run this project

Create AWS Profile and run following Copilot CLI command.

```
export AWS_PROFILE=usertest
copilot init
```

## Access to API

Open browser or use curl to access to the App Runner access point. 

```
curl -l https:<service id>.awsapprunner.com/fruit/prices
or
curl -l https:<service id>.awsapprunner.com/fruit/prices/1
```
