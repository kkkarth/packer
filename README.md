# Packer multi-platform VM image building project


## Getting started

# Switch to Packer project directory.
$ cd /opt/kickstart-packer

# Initialize Packer template.
$ packer init module/ubuntu-linux-24-04/virtualbox/amd64/server/main.pkr.hcl

# Validate Packer template.
$ packer validate module/ubuntu-linux-24-04/virtualbox/amd64/server/main.pkr.hcl

# Build VM image using Packer template.
$ packer build --force module/ubuntu-linux-24-04/virtualbox/amd64/server/main.pkr.hcl



## Get support
- [Issues](https://github.com/kkkarth/packer/issues)

 