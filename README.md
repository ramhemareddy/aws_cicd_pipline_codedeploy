# Ram Hemareddy AWS CICD Pipeline Code Deployment to AWS EC2 Instance



#!/bin/bash \n
sudo yum -y update\n
sudo yum -y install ruby\n
sudo yum -y install wget\n
cd /home/ec2-user
wget https://aws-codedeploy-ap-south-1.s3.ap-south-1.amazonaws.com/latest/install
sudo chmod +x ./install
sudo ./install auto
sudo yum install -y python-pip
sudo pip install awscli
