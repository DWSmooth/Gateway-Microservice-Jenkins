# Gateway-Microservice

A gateway microservice utilizing Spring Cloud Gateway

## Details

This is a fork to work on building a jenkinsfile to build the main maven project and push it as an image to an AWS container.
The jenkinsfile is in the /JenkinsDevWindows/ branch, and at last check was running best from a local Jenkins server.
Running the job on a small EC2 instance with Jenkins bottomed out the instance's resources for more than an hour without finishing,
while locally it would build and push in about 40 minutes.
