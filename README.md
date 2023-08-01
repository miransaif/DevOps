#DevOps CI/CD Pipeline Code
While creating an Instance in AWS select AMI "Ubuntu"
configure proper security groups whcih includes allowing Http and SSH
in user date add this code
"sudo apt update
sudo apt install ruby-full
sudo apt install wget
cd /home/ubuntu
wget https://aws-codedeploy-ap-south-1.s3.ap-south-1.amazonaws.com/latest/install
chmod +x ./install
sudo service codedeploy-agent start"
For a list of bucket names and region identifiers see https://docs.aws.amazon.com/codedeploy/latest/userguide/resource-kit.html#resource-kit-bucket-names
