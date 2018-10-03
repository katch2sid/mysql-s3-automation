# mysql-s3-automation
Automatic Daily DB Backup from linux server to s3 bucket of aws

# Create S3 Bucket 

https://docs.aws.amazon.com/AmazonS3/latest/user-guide/create-bucket.html

# Create the Access Keys to access the bucket

https://aws.amazon.com/premiumsupport/knowledge-center/create-access-key/

# Install AWS CLI 

pip install awscli
https://aws.amazon.com/cli/

# Set Cron Job on the server

0 0 * * * root /usr/bin/[file_name.sh]

