# Lesson-19-Notes
Step-by-step instruction on how to SSH connect to EC2

In conclusion section, the instructor asked students to complete an exercise. While doing the practice, I encountered numerous difficulties.I would like to document the steps that I took to overcome these obstacles.

1. Create an EC2 instance on AWS console. 
2. Create a private VPC, make sure DNS hostname is enabled.
3. Create a subnet
4. Create IAM role and attach to EC2 instance
5. Create Security Group for the instance
6. Create internet gateway and attach to the VPC created
7. Create Route table to VPC  
8. ssh -i my_rsa_key ec2-user@ec2-198-51-100-1.compute-1.amazonaws.com (Public DNS name)
