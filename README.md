# terraform
Terraform handson

https://www.terraform.io/downloads.html
https://releases.hashicorp.com/terraform/0.12.9/terraform_0.12.9_linux_amd64.zip

href="https://releases.hashicorp.com/terraform/0.12.24/terraform_0.12.24_linux_amd64.zip"

### Below all commands utilized on RHEL 8 linux

### update softwares
yum update -y

### install wget util (to download file from internet)
yum install wget -y

### To download terraform zip from internet
wget -q https://releases.hashicorp.com/terraform/0.12.9/terraform_0.12.9_linux_amd64.zip

### to install unzip util on machine
yum install unzip -y

### to unzip the file with -d(destination) to /user/local/bin (so tearrform command added in path)
unzip -o terraform_0.12.9_linux_amd64.zip -d /usr/local/bin

### this will remove the zip file we downloaded with wget
rm terraform_0.12.9_linux_amd64.zip

### all doen check the terrform version
terraform -version

### for pip3
dnf install python3-pip
yum install python3-pip
