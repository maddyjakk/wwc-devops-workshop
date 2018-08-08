### LAB 01

**Step 1:** Create an AWS account

**Step 2:** Create an S3 bucket

Go to AWS console -> Services -> S3 -> Create Bucket -> Provide a Bucket name -> Select Region ->  click Next -> click Next -> Click Next -> Create Bucket

**Step 3:** Create an sns topic

Go to AWS console -> Services -> SNS -> Create a Topic ->  Provide Topic Name -> Create Topic -> Click on the ARN -> Create Subscription -> Protocol(Email) ->  End point (provide email address)

**Step 4:** Create key pair

Go to AWS console-> Services -> EC2 -> Key Pairs -> Create key pair -> Provide Key Pair name -> Save the pem key

**Step 5:** Download the wwc-demo template from http://bit.ly/wwc-dw

**Step 6:** Update Security Groups, Subnets, S3 bucket, sns topic parameters in the template based on your individual aws account
