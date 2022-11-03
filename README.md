# week5-terraform

# Setup
    1.  Clone the repository which contains main.tf file to setup Terraform Infrastructure.
    
    2.  Create .gitignore for:
          -  .terraform/
          -  *.tfstate
          -  *.tfstate.backup
          -  secret_keys_file or .env
    
# Terraform    

    1.  Install Terraform via sudo apt-get install terraform
          -  installation can be confirmed by checking version "terraform --version"
          -  if not done so already, docker needs to be installed as well
    
    2.  Use command "terraform init" to initialize the project and download the plugins for terraform and docker
    
    3.  Use command "terraform apply" where main.tf is in order to create the resources, droplets, vpc, etc...
    
