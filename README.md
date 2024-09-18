# simple-aws-uploader-cli
A simple AWS custom CLI that let's you upload files to your bucket.
# prerequisites
You need to have an AWS account.<br>
You need to have AWS CLI installed locally and configured to work with S3 actions.<br>
You can use the root user(not recomanded).<br>
Best practice is to create a user and add Policies with IAM.<br>
After configuring an IAM user and their policies and roles, configure your AWS CLI to make sure that the settings are set in place.<br>
First make sure that you run the <b>add2path</b> script so that you can use clouduploader globlly.
# environment variables
You can manually add export:<br> <b>ROD_CLOUDUPLOADER_AWS_BUCKET="your-aws-s3-bucket"</b> to the ~/.bashrc file.<br>
Hopefully you are using a user and not the root user.
# commands
You can add a default bucket to your system by using:<br> <b>clouduploader --set-bucket example-bucket-name </b>
<br>This should be the first command that you execute to make sure you are using the right bucket for uploads.<br>
After setting the bucket run:
<br><b>source ~/.bashrc</b> to reload the changes made in the .basrc file in your current terminal<br>
Do this process each time after you set/change your bucket name.<br>
You can use <b>--get-bucket</b> flag to make sure that the bucket is set and it's the right one.
