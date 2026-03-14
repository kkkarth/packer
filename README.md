# Packer multi-platform VM image building project


## Getting started
bash
# Switch to SloopStash Packer kit directory.
$ cd /opt/kickstart-packer
# Initialize Packer template.
$ packer init module/ubuntu-linux-24-04/virtualbox/amd64/server/vagrant.pkr.hcl

# Validate Packer template.
$ packer validate module/ubuntu-linux-24-04/virtualbox/amd64/server/vagrant.pkr.hcl

# Build VM image using Packer template.
$ packer build --force module/ubuntu-linux-24-04/virtualbox/amd64/server/vagrant.pkr.hcl


## Get support
- [Issues](https://github.com/kkkarth/packer/issues)

 