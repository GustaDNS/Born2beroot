# BORN2BEROOT

**BORN2BEROOT** is a project from the 42 Network curriculum that serves as an introduction to system administration and the concept of "root" (superuser) access on Linux systems. The main objective of this project is to teach students the basics of setting up, configuring, securing, and automating a Linux server environment from scratch. It’s a key project for those who want to understand how servers are managed and configured.

The project aims to provide a practical understanding of system administration and various Linux tools. By working through this project, students gain hands-on experience with configuring and securing a server, making them more comfortable in working with Linux and system-level tasks.

## Objective

The main objective of this project is to create a script that:

1. **Installs and configures a basic operating system**: The script sets up a clean Linux environment, ensuring that the system has the essential packages for development and administration.
2. **Configures root access**: The root user’s access is secured and configured correctly, ensuring only authorized individuals can access the server with elevated privileges.
3. **Installs and configures SSH**: Configures a secure connection method for remote access to the server via SSH, allowing system administrators to manage the server remotely.
4. **Applies security practices**: Implements proper security measures like setting up firewalls, restricting access, and ensuring minimal exposure to risks.
5. **Prepares the system for administrative tasks**: The system is configured in a way that it can be used for ongoing administrative work and future configurations.

## Project Description

In the **BORN2BEROOT** project, students are tasked with setting up a Linux server from a clean installation. The entire setup process is automated with a bash script, which configures the system according to specific requirements. The goal is to create a server that is secure, stable, and functional, and that can be used by administrators to perform further configurations.

The project involves learning and applying a range of system administration tasks, such as user and group management, configuring system services, securing the server environment, and automating tasks. By completing this project, students gain an essential skill set for managing Linux systems.

### Concepts and Tools Used

Throughout this project, students work with a variety of tools and concepts that are essential for system administration:

- **IP Configuration and Networking**: Understanding IP addresses and network configuration is crucial when setting up a server. This project teaches how to configure networking settings, troubleshoot network issues, and assign IP addresses.
  
- **SSH (Secure Shell)**: Students learn to set up SSH, which allows secure remote access to the server. This includes configuring SSH keys, adjusting SSH settings, and ensuring that access is restricted to trusted users.

- **System Administration**: The project focuses on essential administrative tasks, such as user creation and permission management. Students learn to use tools like `sudo`, `useradd`, `chmod`, and `chown` to manage users and file permissions.

- **Firewall Configuration**: The project involves configuring the firewall to ensure that only necessary services are exposed to the outside world. Students will become familiar with tools like `ufw` or `iptables` for managing firewall rules.

- **Package Management**: The project also covers installing and managing packages on a Linux system using package managers like `apt` (for Ubuntu/Debian-based systems). Students learn to install essential tools and libraries needed for the server to function properly.

- **Ports and Services**: Understanding how to configure and manage system services is crucial. Students will work with tools like `systemctl` to enable or disable system services, as well as configure which ports should be open for different services (e.g., SSH running on port 22).

- **Permissions and Security**: Students are introduced to security concepts such as configuring user permissions (`chmod`, `chown`), securing the root account, setting up firewalls, and understanding how to minimize vulnerabilities in the system.

- **Automation**: One of the core elements of this project is the automation of system configuration via a bash script. Students write a script that automates the installation and setup of the server, which saves time and reduces human error.

### Key Features:

- **System Setup and Configuration**: The script configures a clean Linux environment by installing essential packages, setting up users and groups, and configuring the network.
- **SSH Setup and Security**: Configures SSH to allow secure remote access, including setting up SSH keys and securing root access.
- **Firewall and Port Management**: Students configure the firewall to limit incoming connections, ensuring that only necessary ports (e.g., port 22 for SSH) are open.
- **Automated Server Setup**: The entire configuration process is automated, reducing the need for manual intervention and ensuring consistency.
- **User and Group Management**: Creates system users with appropriate permissions, ensuring the system is secure and only authorized users can access sensitive resources.

### Prerequisites:
- A Linux machine or virtual environment.
- Root privileges to run the script.
