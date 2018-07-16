# aws-mfa-cli
How to script MFA for AWS CLI


If you are using the AWS platform from the command line you have configured your terminal for CLI access using an AWS Access Key ID and an AWS Secret Access Key. As a result, those values are saved in the ~/.aws/credentials file, i.e. there is a file in your computer in which the AWS account credentials are stored in plain text. Consequently, if your computer is stolen or hacked, a malicious user can use your credentials and then use the AWS CLI tool to do whatever you are privileged to do in your AWS account. Adding MFA to the CLI access will add a significant hurdle for the intruder since they also need your MFA device in addition to your AWS access keys before he or she can do any harm.

