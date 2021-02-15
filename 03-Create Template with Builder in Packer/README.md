## Learning Objectives

* Template is your instruction file for OS image build
* Templates are authored in JSON or Hashicorp Configuration Language (HCL2) v2 syntax
* Several sections to the template file:
  * Builders - back-end service that will be used to build an image (VirtualBox, AWS, Hyper-V, Azure)
  * Provisioners - commands to set up the VM
  * Communicators - send files to the VM via SSH or Windows Remote Management (WinRM) remoting protocols

* Need to specify a base AMI ID. You can use Amazon's managed images or your own custom image.
  * Base AMI must be in the same region as your EC2 build process
  
* Packer creates temporary SSH key pair to connect to the EC2 instance