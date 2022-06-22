**Aplicação Node JS**

Veja o arquivo AWS.pdf ou o vídeo tutorial no Youtube. 

Install Git
Install Vscode
Create account IAM
Create Repo CodeCommit

Abrir o GitBash

```
git init
git config --global user.name "Describe Name"
git config --global user.email "email"
git config --global credential.UseHttpPath true
git remote add origin https://repo
```

```
#!/bin/bash
sudo yum update -y
sudo yum install ruby -y
sudo yum install wget -y
sudo yum install httpd -y
cd /home/ec2-user
wget https://aws-codedeploy-us-east-1.s3.us-east-1.amazonaws.com/latest/install 
chmod +x ./install
sudo ./install auto
sudo service codedeploy-agent status
sudo service codedeploy-agent start
sudo systemctl start httpd.service
sudo systemctl enable httpd.service
```

#Qual região estiver https://docs.aws.amazon.com/codedeploy/latest/userguide/resource-kit.html#resource-kit-bucket-names


