# simple-aws-uploader-cli
A simple AWS custom CLI that let's you upload files to your bucket.
# prerequisites
You need to have an AWS account.<br>
You need to have AWS CLI installed locally and configured to work with S3 actions.<br>
You can use the root user(not recomanded).<br>
Best practice is to create a user and add Policies with IAM.<br>
After configuring an IAM user and their policies and roles, configure your AWS CLI to make sure that the settings are set in place.<br>
# environment variables
You can manually add export ROD_CLOUDUPLOADER_AWS_BUCKET="your-aws-s3-bucket" to the ~/.bashrc file.<br>
Hopefully you are using a user and not the root user.
# commands
You can add a default bucket to your system by using: <b>clouduploader --set-bucket example-bucket-name </b>
This should be the first command that you execute to make sure you are using the right bucket for uploads.
