# Terraform Docker

This project uses Terraform to build a Docker container for an Nginx web server.

## Prerequisites

Ensure you have the following software installed on your machine:

- [Terraform](https://learn.hashicorp.com/tutorials/terraform/install-cli)
- [Docker](https://docs.docker.com/get-docker/)

### Terraform Installation

Choose the appropriate installation instructions for your operating system:

- [Linux](https://learn.hashicorp.com/tutorials/terraform/install-cli#install-terraform)
- [Windows](https://learn.hashicorp.com/tutorials/terraform/install-cli#windows)
- [Mac](https://learn.hashicorp.com/tutorials/terraform/install-cli#macos)

### Docker Installation in Linux

```
sudo apt-get install docker.io -y

# Add user to the docker group for safer side
sudo usermod -aG docker $USER

# Check if Docker is running
docker ps

Terraform Commands
Initialize the Terraform working directory:



terraform init
Apply the Terraform configuration:



terraform apply
Verify Docker Container and Image
Check the created Docker image and running container:



docker image ls

docker ps -a
Cleanup
To remove the Docker container and image created by Terraform:



terraform destroy
Enter 'yes' when prompted.

Contributing
If you encounter issues or have suggestions for improvement, feel free to open an issue or create a pull request.

License
This project is licensed under the MIT License - see the [LICENSE file]([url](https://github.com/HesterHDM/Terraform_docker/blob/main/LICENSE)) for details.
