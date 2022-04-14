# Deploy the application using CLI

1. Navigate to server directory, run `eb deploy` to deploy a version of the application to the server,please note that you may need to run `eb use <application-name>` first.
2. Navigate to Client-Side directory, run `aws s3 cp --recursive --acl public-read ./www s3://<BUCKET-NAME>/` to deploy the frontend files to AWS S3.