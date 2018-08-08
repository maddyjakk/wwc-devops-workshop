### LAB02

Please work through Lab01 before starting this section.

**Step 1:** Update the inbound traffic rules of the security group in AWS

  Goto AWS console-> Services -> EC2 -> Security Groups(From Left pane) -> Click on the default security group -> Goto Inbound rules ->     Click on Edit -> Add All traffic port 0.0.0.0/0 -> Add one more All Traffic port ::/0

**Step 2:** Upload the template to S3 Bucket (optional)

**Step 3:** Create the stack

  Goto AWS console-> Services -> CloudFormation -> Create Stack -> Choose a template (Upload a template to Amazon S3)-> Choose file from 
  local-> enter a stack name -> click Next -> click Next -> Create
