# Automation-Cloudformation
This CloudFormation  deploy scalable   instances of web server serving one webpage
# Project Objective
        * Script shall deployed scalable  instances of a web server
        * Deployed System only serve one html web page pulled from S3 
        * System shall secure this application and host such that only appropriate ports are publicly exposed  
        * Any http requests should be redirected to https
        * System may use a self-signed certificate for the web server
   # The AWS  env includes: 
  * Amazon Linux
  * Apache web server instance that uses  Auto Scaling and Elastic Load Balancing 
  * CloudWatch alarms that execute Auto Scaling policies to scale up or down when the defined thresholds are exceeded
  * AWS Elastic Load Balancing (ELB) is used to redirect http/https traffic to the web servers. 
  * Pull the index web page from S3.
  * SNS for notification during the scaling process.
  * A self-signed certificate is being generated and used by the ELB.
        
