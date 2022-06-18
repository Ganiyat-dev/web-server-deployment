# web-server-deployment
This project deploy web servers for a highly available web app using CloudFormation. The scripting code creates and deploys the infrastructure and application for an Instagram-like app from the ground up. By deploying the networking components, followed by servers, security roles and software

## below is the link to the infrastructure diagram
![Udagram Infrastructure Architecture](https://user-images.githubusercontent.com/60348108/174415448-704381ba-c374-4f4b-963d-3ddd850716b1.png)


## Network Stack Creation
![networkStack](https://user-images.githubusercontent.com/60348108/174414741-f1811018-fc96-46b6-948b-449b05ff9e49.png)

## Server Stack Creation
![serverStack](https://user-images.githubusercontent.com/60348108/174414746-53caca18-d505-40c4-972b-75adf3477561.png)

## Running Instances
![Instances running](https://user-images.githubusercontent.com/60348108/174414747-60907977-27c0-4d02-94bc-48797281b0f0.png)

## Security Groups for the Load balancer and Web server
![Security groups](https://user-images.githubusercontent.com/60348108/174414751-6bf52082-aef5-4f61-bf14-e65ba30e2afe.png)

## Target Group
![Target group](https://user-images.githubusercontent.com/60348108/174414752-cb54f542-0045-4595-86a3-74d4afb26e58.png)

## Load Balancer DNS
![Load balancer](https://user-images.githubusercontent.com/60348108/174414754-ca17c822-c734-48a6-a220-8f2cd05d767d.png)

## Link to the web application: http://serve-webap-vfcmzsz3sqvs-2044524630.us-east-1.elb.amazonaws.com/
![url works](https://user-images.githubusercontent.com/60348108/174414757-7a78b741-caa6-4db3-9eb0-5e500f3b7d65.png)
