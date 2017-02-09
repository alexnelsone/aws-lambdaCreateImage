# aws-lambdaCreateImage


## Synopsis

lambdaCreateImage is an AWS lambda function that queries EC2 instances in a region for a tag called ScheduledBackup.  If the value of the tag is 'true' with a lowercase 't', then
an AMI image is made of that instance.  The function runs independently.

## Returns

The function returns True on proper execution. Otherwise, it returns False.  