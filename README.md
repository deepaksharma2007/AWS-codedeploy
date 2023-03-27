# awscodedeploy

sudo yum update -y

sudo yum install -y ruby wget

wget https://aws-codedeploy-eu-west-1.s3.eu-west-1.amazonaws.com/latest/install

(it changes according to the regions:-  wget https://aws-codedeploy-ap-south-1.s3.ap-south-1.amazonaws.com/latest/install)
chmod +x ./install

sudo ./install auto

sudo service codedeploy-agent status

