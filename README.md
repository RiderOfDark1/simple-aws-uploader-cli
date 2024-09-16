# simple-aws-uploader-cli
A simple AWS custom CLI that let's you upload files to your bucket.
# prerequisets
You need to have an AWS account.
You need to have AWS CLI installed locally and configured to work with S3 actions.
You can use the root user(not recomanded).
Best practice is to create a user and add Policies with IAM.
After configuring an IAM user and their policies and roles, configure your AWS CLI to make sure that the settings are set in place.
# environment variables
Add export ROD_CLOUDUPLOADER_AWS_BUCKET="your-aws-s3-bucket" to the ~/.bashrc file.
Hopefully you are using a user and not the root user.
