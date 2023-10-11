# elb_ec2_cloud_formation
A CLOUD FORMATION TEMPLATE THAT CREATES 2 PUBLIC INSTANCES FRONTED BY AN ALB

    Resources Created
    2 Public Subnet 
    1 Route table entries to route traffic to the Internet Gateway for outbound
    1 Internet Gateway (for all outbound traffic)
    1 ELB Security Group with Port 80 open to everyone
    1 EC2 Security Group with Port 80 open to the Load Balancer
    1 ELB Application Load Balancer
    1 EC2 t2.micro linux instance running user data
    1 EC2 Target Group
