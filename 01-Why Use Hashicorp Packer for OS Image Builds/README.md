## Learning Objectives

* Packer is a cross-platform and cloud-agnostic tool to run operating system image builds
* Pre-building operating system images helps you rapidly scale your infrastructure

* Allows you to store your OS image builds as code, so you can version control and automate them
* Integrates with other open source tools to streamline build process, and make your existing knowledge reusable
* You can run builds locally on your system and import them into cloud platforms

* Works with AWS, Azure, Google Cloud, Linode, Digital Ocean, and other VPS services
* Also works with local hypervisors (ie. Hyper-V, VirtualBox, VMware, etc.)

* In addition to operating system image builds, you can also build Linux container images with Docker
* Post-processing steps can take a resulting image and copy 

### Tool Comparison

* Amazon EC2 Image Builder is similar managed service, but has several limitations compared with Packer 
  * EC2 Image Builder is proprietary to AWS
  * Packer is open source, and therefore runs anywhere
  * EC2 Image Builder is very complex
  * Can't use EC2 Spot instances for builds

### What You'll Learn

* Install Hashicorp Packer on your system
* Create a Hashicorp Packer template file from scratch
* Run a Packer build directly in Amazon Elastic Compute Cloud (EC2)
