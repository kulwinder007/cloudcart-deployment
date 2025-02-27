# Cloudformation json scripts for Cloudcart - ecommerce platform hosted on AWS.


Open Cloudformation > create stack > 
Choose an existing template: Upload script file > Next
Enter stack name (no need to modify parameters for now)> Next
Stack failure options: Select "Delete all newly created resources" > Next > Create.

#Note: 
1. Use json scripts in sequence i.e. Part 1, part 1.1, part 2 and so on.
2. When 1st cloudformation stack is created, then only create next stack.
3. When deleting the stack, delete it in decending order.
