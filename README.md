# AWS
Steps to launch an EC2 instance:
1. Login to AWS Console
2. Go to EC2 Dashboard
3. Click "Launch Instance"
4. Choose AMI, instance type, and key pair
5. Configure security group
6. Launch and connect via SSH

   

S3
{
  "Version": "2012-10-17",
  "Statement": [
    {
      "Effect": "Allow",
      "Principal": "*",
      "Action": "s3:GetObject",
      "Resource": "arn:aws:s3:::your-bucket-name/*"
    }
  ]
}
