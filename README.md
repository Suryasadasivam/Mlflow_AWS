mlflow on aws 

1.login to aws console.

2. Create Iam user with administrator access.

3. export the credentials  in your aws cli by running aws configure.
   
4. create a s3 bucket.
  
5.  creat ec2 machine & add security groups 5000 ports


Commands on Ec2 machine 

1. sudo apt update

2. sudo apt install python3-pip

   sudo apt insall pipenv

   sudo apt install virtualenv
   
   mkdir mlflow.

   cd mlflow

   pipenv install mlflow

   pipenv install awscli

   pipenv install boto3

   pip env shell

   aws configure

   mlflow server -h 0.0.0.0 --default-artifact-root s3://mlflow-bucket

   
   


