---
title: "Day 7 Task: Understanding package manager and systemctl"
seoTitle: "Package manager"
datePublished: Wed Jul 26 2023 23:58:37 GMT+0000 (Coordinated Universal Time)
cuid: clkkdzpqp000009jqcqqjfbhq
slug: day-7-task-understanding-package-manager-and-systemctl
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1690415826009/2c1c0a4e-a5fc-4dac-8bc6-206da5145b97.jpeg
ogImage: https://cdn.hashnode.com/res/hashnode/image/upload/v1690415837318/c029a33a-de80-4ab2-b7fa-b6011ca1c010.jpeg
tags: package-manager, linux-for-beginners, jenkins-devops, systemctl

---

**What is a package manager in Linux?**  
A package manager in Linux is a software tool designed to simplify the installation, management, and removal of software packages on a Linux-based operating system. It acts as a centralized and automated system that handles the process of installing, upgrading, configuring, and removing software applications and libraries.

Package managers enable seamless software updates, ensuring that users have the latest bug fixes, security patches, and new features. They also offer mechanisms to remove unwanted software packages while handling associated configurations gracefully.

**What is the package?**  
A package is usually referred to as an application but it could be a GUI application, command line tool or a software library (required by other software programs). A package is essentially an archive file containing the binary executable, configuration file and sometimes information about the dependencies.

### You have to install docker and Jenkins in your system from your terminal using package managers

To install Docker and Jenkins on Amazon Linux, you can use the `Yum` package manager. Here are the steps:

1. Install Docker on Amazon Linux:
    
    ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1690337329780/fe72d54f-69ce-4bca-ae31-2862e204dec0.png align="center")
    

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1690337404560/ef2ba2ee-9c54-4fc6-8313-96da192c612a.png align="center")

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1690337515475/f84075c1-56ec-4dd1-9716-3c83196e4b1c.png align="center")

**Start and enable Docker service:  
Add your user to the "docker" group to avoid using "sudo" with Docker commands:**

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1690339513447/f3cbdeb8-126e-4606-94fc-3e8e165726ff.png align="center")

**Note:** After adding your user to the "docker" group, you need to log out and log back in to apply the group changes.

**Install Jenkins:**

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1690414884247/58912ac0-d2ad-4949-81da-c00317576001.png align="center")

### systemctl and systemd:

Systemctl and systemd are essential components in modern Linux systems that play a crucial role in managing services and processes. Let's explore each of them:

`systemd` is a system and service manager for Linux operating systems. It is designed to replace the traditional SysV init system and brings several advantages, including faster boot times, parallel startup of services, and better management of system resources.  
`systemctl` is a command-line tool that interacts with the systemd service manager. It allows users to control and manage services, view their status, enable or disable them at boot, and more.

Common systemctl Commands:

* `systemctl start service_name`: Start a service.
    
* `systemctl stop service_name`: Stop a service.
    
* `systemctl restart service_name`: Restart a service.
    
* `systemctl enable service_name`: Enable a service to start automatically at boot.
    
* `systemctl disable service_name`: Disable a service from starting automatically at boot.
    
* `systemctl status service_name`: View the status of a service.
    
    **service:**
    
    * `service` is a legacy command that works with the older SysV init system, which was used by many Linux distributions before the widespread adoption of systemd.
        
    * While `service` can still be found on many systems, it is essentially a compatibility command for managing SysV-style init scripts.
        
    * `service` is simpler in functionality compared to `systemctl` and lacks some of the more advanced features provided by systemd
        
        *Thank you for joining me on this exciting DevOps journey! I hope you found this blog insightful as we explored package managers, Docker, Jenkins, and systemctl commands. Keep learning, experimenting, and pushing the boundaries of your DevOps skills. Stay tuned for more exciting content in my future blogs*