# AutoScaleGroupAWS
This project creates a auto scaling group in AWS

Creating one VPC with 4 different subnets 2 public and 2 private. 

The auto scaling group creates 2instances in the private subnets and installs nginx on both

A cloudwatch alarm is set to scale the instances once the CPU is equial or more than the threshold 

Traffic is distributed trough a application load balancer on port 80 
