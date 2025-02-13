# ce9-assignment-2.8


AWS CLI Command to deploy new version in aws. 

aws elasticbeanstalk create-application-version 
--application-name norman-test-1 
--version-label 0.0.0.4 
--source-bundle S3Bucket=<my-bucket-name>,S3Key=<python.zip uploaded to s3>
