# Serverless-101-CS50
Notes from Serverless 101 CS50 - https://www.youtube.com/watch?v=CBo2iMst6zE

## What is Serverless?
Serverless is a cloud-native development model that allows developers to build and run applications without having to manage servers.There are
still servers in serverless, but they are abstracted away from app development. A cloud provider handles the routine work of provisioning, maintaining,
and scaling the server infrastructure. Developers can simply package their code in containers for deployment. Once deployed, serverless apps respond 
to demand and automatically scale up and down as needed.

## Why serverless?
- No server management
- Developers are only charged for the server space they use, reducing cost
- Serverless architectures are inherently scalable
- Quick deployments and updates are possible
- Code can run closer to the end user, decreasing latency



### Lambda Function
AWS Lambda is a serverless, event-driven compute service that lets you run code for virtually any type of application 
or backend service without provisioning or managing servers.  
AWS Lambda is a serverless computing service provided by Amazon Web Services (AWS). Users of AWS Lambda create functions, self-contained applications written in one of the supported languages and runtimes, and upload them to AWS Lambda, which executes those functions in an efficient and flexible manner.
The Lambda functions can perform any kind of computing task, from serving web pages and processing streams of data to calling APIs and integrating with other AWS services.
The concept of “serverless” computing refers to not needing to maintain your own servers to run these functions. AWS Lambda is a fully managed service that takes care of all the infrastructure for you. And so “serverless” doesn’t mean that there are no servers involved: it just means that the servers, the operating systems, the network layer and the rest of the infrastructure have already been taken care of, so that you can focus on writing application code.
