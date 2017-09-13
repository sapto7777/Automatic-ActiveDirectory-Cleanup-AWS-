# Automatic-ActiveDirectory-Cleanup-AWS-
This contains a cloudformation template to automatically deploy in accounts in order to perform a automation process.
The cloudformation template will automatically delete terminated instances at the aws end from the Microsoft Active Directory.
The main issue this code solves is that when instances are terminated at aws console, they dont get automatically deleted at the Active Directory end.
Here using AWS lambda, AWS cloudwatch , SSM agent I developed a lambda function to automatically delete objects from end triggered by Cloudwatch at the AWS end.
