# Fileware

**Fileware** is a simple CLI tool that allows users to fetch and edit template files for popular DevOps tools like Ansible, Kubernetes, Docker Compose, CI Pipelines, and Terraform. It simplifies the process of getting started by providing users with demo template files that they can modify and save locally.

## Features

- Provides ready-to-use templates for:
  - Ansible
  - Kubernetes Deployments
  - Docker Compose
  - CI Pipelines
  - Terraform
- Easily fetch templates from GitHub.
- Edit templates directly in the terminal using `nano`.
- Saves modified templates to the current working directory(By-Default).
- Avoid clutter: files are only saved if modified.
  
## Installation

### Download & Install `.deb` Package

1. **Download the `.deb` file**:  
   You can download the latest version of Fileware from the [Releases page](https://github.com/Amrendra1111/fileware/releases/tag/v1.0.0).

2. **Install the `.deb` file**:  
   Once downloaded, you can install Fileware using the following command:==>
   sudo dpkg -i fileware_v1.0.0.deb

3. **Verify Installation**:
After installation, run the following command to verify that Fileware is installed and view available commands:
fileware
You should see a list of available commands.

4. **Usage**
To get started with Fileware, open your terminal and type "fileware". This will show you the available commands and templates:
fileware

**Available templates	and                           Commands**
1.  Ansible                             (fileware ansible-template)
2.  Kubernetes Deployment               (fileware k8s-deployment-template)
3.  Kubernetes Service                  (fileware k8s-service-template)
4.  Kubernetes Configmap                (fileware k8s-configmap-template)
5.  Kubernetes Secret                   (fileware k8s-secret-template)
6.  Docker Compose                      (fileware docker-compose-template)
7.  Docker Compose Build                (fileware docker-compose-build-template)
8.  Terraform S3                        (fileware terraform-s3-template)
9.  Terraform Ec2                       (fileware terraform-ec2-template)
10. Terraform Iam                       (fileware terraform-iam-template)
11. Terraform Security Group            (fileware terraform-sg-template)
12. Terraform Subnet                    (fileware terraform-subnet-template)
13. Terraform Vpc                       (fileware terraform-vpc-template)


**Fetching and Editing Templates Example:**

To fetch and edit a template, use one of the following commands:

**Ansible Template**:

fileware ansible-template

**Kubernetes Deployment Template**:

fileware k8s-deployment-template

**Kubernetes Configmap Template**:

fileware k8s-configmap-template

**Kubernetes Secret Template**:

fileware k8s-secret-template

**Kubernetes Service Template**:

fileware k8s-service-template

**Terraform S3Template**:

fileware terraform-template

and so on....


**Once the template is fetched, it will be opened in nano. If you edit and save the file, it will be stored in your current working directory.**

**NOTE** Make sure to rename the file after editing or else the file will not be saved.

**Removing Fileware**:

If you wish to uninstall Fileware, you can do so with the following command:

sudo apt remove fileware


**Contributing**:

Contributions to Fileware are welcome! To contribute:

Fork the repository.

Create a new branch for your feature.

Make your changes.

Submit a pull request.

**License**:

This project is licensed under the MIT License - see the LICENSE file for details.

**Support**:

If you encounter any issues or have any feature requests, please create an issue in this repository or reach out via email.

**Email**:

amrendra1111singh@gmail.com
