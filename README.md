# Server-with-nginx-and-pm2

A simple project with a script for deploying a react project from a git repository to an AWS ubuntu instance using nginx to setup reverse proxy and PM2 to run the project in the background.

## Setup
* Create an AWS account and create an EC2 instance
* SSH into the instance with your IP address and username
* Clone this repository
* copy the selene_deploy.sh file to the root directory
* create a .env file in the root directory and setup environment variables using the .env.sample file provided in this repo
* In the root directory, run "sudo bash selene_deploy.sh on your terminal"
* Configure your domain name service using AWS Route 53
* Test your app in a browser by visiting your domain name
