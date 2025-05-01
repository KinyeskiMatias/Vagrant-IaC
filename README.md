# Vagrant-IaC
This is a small project to practice automation using Vagrant. It involves setting up a CentOS Stream 9 virtual machine, automating the installation of essential tools (httpd, wget, unzip, git), deploying a sample website (Mini Finance template), and configuring a functional web server.

# Automated Vagrant Environment for Web Server Setup

## Project Overview
This project uses Vagrant to automate the setup and provisioning of a CentOS Stream 9 virtual machine. By leveraging Vagrant's capabilities and shell provisioning scripts, the project installs and configures a web server (`httpd`) and deploys a sample website (Mini Finance template).

## Features
- **Automated Virtual Environment**: Quickly set up a CentOS VM using Vagrant.
- **Web Server Installation**: Installs and configures `httpd`.
- **Website Deployment**: Downloads, unzips, and deploys the Mini Finance website template.
- **Network Configuration**:
  - Private Network with IP `192.168.56.17`.
  - Public Network (bridged).
- **Cleanup Process**: Removes temporary files used during provisioning.

## How to Run
1. **Install Prerequisites**:
   - [Vagrant](https://www.vagrantup.com/downloads)
   - [VirtualBox](https://www.virtualbox.org/)
2. **Clone the Repository**:
   ```bash
   git clone <your-repository-url>
   cd <your-repository-folder>
