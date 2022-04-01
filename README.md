# Project1 Terraform EC2 Instance Integrating With Ansible Playbooks

###PROJECT DESCRIPTION

> In this project I have created a terraform script which will launch an ec2 instance with some basic configurations

> Along with this instance it will create an ebs volume of size 10 GB and attach it to this particular instance

> After the instance is configured it will update the instance public ip into the ansible inventory file

> And the ansible script will run which will configure the necessary packages like php apache2 for webserver setup

> And also using the ansible script it will format the attached ebs volume and mount it to the /var/www/html directory

> And clone the particular git repos into that directory which can then be stored persistently 

https://user-images.githubusercontent.com/64367344/161302110-1c8023a0-c9e4-4438-93fe-3b78f15f0cb8.mp4
