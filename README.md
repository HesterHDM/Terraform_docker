# Terraform_docker
Terraform code to build docker containers
Make sure you have installed the terraform and docker on your machine

# Terraform Installation
Choose your appropriate OS -Linux/Windows/Mac
[CLI_Installation](https://developer.hashicorp.com/terraform/tutorials/aws-get-started/install-cli)

# Docker installation in Linux
sudo apt-get install docker.io -y

#add user to docker group for safer side
usermod -aG docker $USER

#check if docker is running or not by using:
docker ps 

# Terraform commands
terraform init
terraform apply

# verify docker container and image
docker image
docker ps -a
