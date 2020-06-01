![](images/AWSWebAPP.png)

This repository contains a CloudFormation script to create the web app for the final project of the Deploy Infrastructure as Code (IAC) course in the Udacity Cloud DevOps Nanodegree. 

Running the `master.yml` script will create a high availability web app running on four web servers across two availability zones on the AWS Cloud. 


## Deployment Steps
Clone the repository then run the following command:

```
aws ./create.sh udagram master.yml parameters.json
```
