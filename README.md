# DevOps IWS Entry Level

This is a project used to test potential candidates that are interested in a DevOps position. It is composed of several projects and you will be asked to complete one or more as a part of your interview.

We are primarily a Python shop, so projects submitted in Python are preferred. However, if you feel like another language is better suited for your solution feel free to impress us!

## AWS Stack Design

Using [Rekognition](https://aws.amazon.com/rekognition/), [Lambda](https://aws.amazon.com/lambda/) and [S3 Object Tagging](http://docs.aws.amazon.com/AmazonS3/latest/dev/object-tagging.html) design a service that will automatically tag newly uploaded images with the top 3 labels returned by Recognition. Please provide us with instructions on how to test and operate your service (either using IAM user credentials or other custom interface). If you provide IAM credentials please include the JSON policy as well.

Bonus points will be awarded for extra features outside of the basic requirements. Here are some ideas:
 * a custom [CloudWatch dashboard](http://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/CloudWatch_Dashboards.html) to monitor the health of the service
 * a [CloudFormation](https://aws.amazon.com/cloudformation/) manifest or other similar tool ([Terraform](https://www.terraform.io/), etc) to describe the entire service
 * a hosted web UI or custom API for your service
 
## Virtual Machine Stack Debugging
 
We have prepared a [VirtualBox](https://www.virtualbox.org/) image for you to debug.
TBA
