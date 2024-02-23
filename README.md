# TerraformCodeHA
High Availability Infrastructure using Terraform.

Provision Highly Availabe Web Cluster in any Region Default VPC
Create:
    - Security Group for Web Server and ALB
    - Launch Template with Auto AMI Lookup
    - Auto Scaling Group using 2 Availability Zones
    - Application Load Balancer in 2 Availability Zones
    - Application Load Balancer TargetGroup
 Update to Web Servers will be via Green/Blue Deployment Strategy