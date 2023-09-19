# Automate an Elastic Beanstalk Deployment

## Purpose
* The purpose of this project is to automate an Elastic Beanstalk Deployment.

## Issues

## Steps

### 1.
* Create an EC2
* Install Jenkins
* Install python3.10-venv
* Install unzip
* Install python-pip
* Access Jenkins on port:8080

### 2.
* Create a multibranch Pipeline
* Integrate GitHub with Jenkins
* Build the multipipeline branch pipeline. You should receive success.
<img width="749" alt="Screen Shot 2023-09-17 at 10 44 45 PM" src="https://github.com/DarrielleEvans/AutomateDeployment/assets/89504317/647efe71-0020-4202-a8e6-fcbfcc77c789">

### 3.
* Install cli
* Sign into Jenkins
* Install ebcli
* Copy the url from the terminal to access application

<img width="1454" alt="Screen Shot 2023-09-18 at 7 18 39 PM" src="https://github.com/DarrielleEvans/AutomateDeployment/assets/89504317/04601691-8429-44c2-84ec-3764995139c8">

### 5.
* Add the following code to your jenkins file and observe the jenkins pipeline:
  stage ('Deploy') { steps { sh '/var/lib/jenkins/.local/bin/eb deploy' } }
  <img width="790" alt="Screen Shot 2023-09-18 at 8 58 44 PM" src="https://github.com/DarrielleEvans/AutomateDeployment/assets/89504317/a2770c48-aa10-4003-968a-5a4aaf3c59de">

### 4.
* Create a webhook from your main repo
* payload url = HTTP://http://yourIP:8080/github-webhook/
* Payload will build a 


## Technologies Used
* AWS EC2
* AWS Beanstalk
* Jenkins
* GitHub
## Optimization
