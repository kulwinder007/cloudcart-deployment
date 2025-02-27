# Cloudformation json scripts for Cloudcart - ecommerce platform hosted on AWS.


Open Cloudformation > create stack > 
Choose an existing template: Upload script file > Next
Enter stack name (no need to modify parameters for now)> Next
Stack failure options: Select "Delete all newly created resources" > Next > Create.

#Note: 
1. Use json scripts in sequence i.e. Part 1, part 1.1, part 2 and so on.
2. When 1st cloudformation stack is created, then only create next stack.
3. When deleting the stack, delete it in decending order.


Below is the updated subnet details for our architecture:

VPC: 10.0.0.0/16

Availability Zone 1 (us-east-1a):
Public Subnet (Bastion Host): 10.0.1.0/24
Private Subnet (Web Servers): 10.0.2.0/24
Private Subnet (App Servers): 10.0.3.0/24
Private Subnet (Database): 10.0.4.0/24

Availability Zone 2 (us-east-1b):
Public Subnet (Bastion Host): 10.0.11.0/24
Private Subnet (Web Servers): 10.0.12.0/24
Private Subnet (App Servers): 10.0.13.0/24
Private Subnet (Database): 10.0.14.0/24
