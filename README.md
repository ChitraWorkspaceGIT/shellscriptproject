###SHELL SCRIPTING PROJECT###

Create an EC2 instance 

Name: shellscriptProject
Ubuntu
t2.micro
Select key pair
8GB Storage
Connect to instance

```vim aws_resource_list.sh ```

Go to github gists 
paste the script
:wq

```chmod +x aws_resource_list.sh```

```./aws_resource_list.sh us-east-1 ec2```

error:aws cli install

Go to aws documentation

linux--> curl command
zip and aws install command 
copy and paste it

```./aws_resource_list.sh us-east-1 ec2```

error: aws configure

Go to security credentials create access and secret access keys

```aws configure```

paste access key
paste secret access key
us-east-1

```./aws_resource_list.sh us-east-1 ec2```

This command is used to list the instances

```./aws_resource_list.sh us-east-1 s3```

This command is used to list the s3 buckets
