#Terraform AWS EC2 Module

##Inputs:

ami_id (optional): default value is "ami-09c813fb71547fc4f"
security_group_ids (optional) : list of  security group ids. default is sg-012ccd9fbfefc96b7
instance_type(optional): default value is t3.micro
tags(optional): default value is empty

##outputs

public_ip: outputs the public ip i instance  created
private_ip : output the private ip  instance created 
instance_id : output the instance id instance created

