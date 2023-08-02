---
title: "💻Deep Dive in Git & GitHub for DevOps Engineers."
seoTitle: "Deep Dive in Git & GitHub for DevOps Engineers."
datePublished: Sun Jul 30 2023 19:22:32 GMT+0000 (Coordinated Universal Time)
cuid: clkptw2c9000a09msfyh2htwb
slug: deep-dive-in-git-github-for-devops-engineers
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1690744756348/b16aa3b4-0eab-4594-a41a-550e86ccd30f.png
tags: github, git, cloud-computing, devops, git-github-version-control-linux-git-commands-github-repositories-cheat-sheet-git-branching-git-workflow-collaboration-git-history-git-commit-git-merge-git-rebase-git-pull-request-git-fork-git-stash-git-remote-git-ignore-git-hooks-github-issues-github-actions-github-pages-github-security-git-for-beginners-advanced-git-techniques-github-collaboration-git-integration-git-flow-git-best-practices

---

🚀**What is Git and why it's important?**

Git is a version control system that helps developers track and manage changes in their code, making collaboration easier and providing a safety net for code backups and version history.

**Its importance lies in the following key points:**

**Version Control:** Git tracks changes in source code, allowing developers to view, compare, and revert to previous versions easily.

**Collaboration:** It enables multiple developers to work on the same codebase simultaneously, facilitating seamless collaboration.

**Branching and Merging:** Git allows developers to create branches to work on new features or bug fixes independently and later merge them back into the main codebase.

**Code Integrity:** With Git, changes are cryptographically hashed, ensuring the integrity and authenticity of code throughout the development process.

**Backup and Recovery:** Git stores code on local machines and remote repositories, offering a robust backup and recovery system.

### 🚀**What is GitHub?**

GitHub is a web-based platform that provides hosting for Git repositories. It allows developers to store, manage, and collaborate on their code, making it easier to work together and contribute to open-source projects.

### 🚀**Difference between Git and Git Hub?**

| **Git** | **GitHub** |
| --- | --- |
| Distributed version control system (VCS). | Web-based hosting platform for Git repositories. |
| Tracks changes in source code files. | Provides an interface for managing Git repositories. |
| Operates locally on a developer's machine. | Allows remote access to repositories via the web. |
| Doesn't require a centralized server. | Offers social and collaboration features. |
| Supports branching, merging, and history. | Facilitates pull requests, issue tracking, and more. |
| The command-line tool is usable independently. | Enhances team collaboration and open-source projects. |

**🚀What is the difference between local & remote repositories?**

The main difference between local and remote repositories lies in their location and usage in the context of version control systems like Git.

**Local Repository:**

1. **Location:** A local repository is located on your own computer or development environment.
    
2. **Usage:** It is the version of the repository that you work with directly. When you create a new project or clone an existing one, you get a local repository.
    
3. **Operations:** You perform all your day-to-day development tasks in the local repository, such as creating, modifying, and committing code changes.
    
4. **Independence:** Local repositories can be used even when there is no internet connection or connection to a remote server.
    

**Remote Repository:**

1. **Location:** A remote repository is hosted on a server or a cloud-based platform like GitHub, GitLab, or Bitbucket.
    
2. **Usage:** It serves as a central, shared repository where developers can collaborate and exchange code changes.
    
3. **Operations:** Developers push their committed changes from the local repository to the remote repository to share them with others.
    
4. **Collaboration:** Multiple developers can access and work on the same remote repository, allowing them to collaborate on a project simultaneously.
    
5. **Backup and Sharing:** Remote repositories act as a secure backup of the codebase and enable easy sharing with other team members.
    

In summary, local repositories are on your local machine, where you do most of your coding and version control tasks. Remote repositories, on the other hand, are hosted on servers or cloud platforms, providing a centralized location for collaboration, sharing, and backup of the codebase.

**How to connect local to remote?**  
To connect your local repository to a remote repository, follow these steps:  
1\. **Create a Remote Repository**

2\. **Get the Remote Repository URL**

3\. **Initialize Git Locally**

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1690738560614/3ec542bf-9d41-4646-850c-6e1f732b1210.png align="center")

4\. **Add and Commit Your Code Locally**

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1690738585635/ec7b7d1b-f86e-42c2-83a8-5d28eb269923.png align="center")

5\. **Set Up the Remote**

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1690738671159/1986e42a-2052-482a-a478-ee0f8b26dff8.png align="center")

6\. **Push to the Remote Repository**

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1690738696131/8972e449-dc21-474e-857b-6c4f95be2a2f.png align="center")

Now, your local repository is connected to the remote repository. You can continue working on your code locally and use `git push` to send your changes to the remote repository for collaboration and backup. Similarly, you can use `git pull` to get the latest changes from the remote repository to your local repository.

If you are interested in learning about the process of creating a GitHub repository, I invite you to read my blog, where you will find a comprehensive guide detailing all the necessary steps to accomplish this task.

🔍 [https://learnwithshakshi.hashnode.dev/day-8-basic-git-github-for-devops-engineers](https://learnwithshakshi.hashnode.dev/day-8-basic-git-github-for-devops-engineers)

**Concept of Branches in git**

In Git, **branches** are separate lines of development that allow developers to work on different features, bug fixes, or experiments independently from the main codebase. Each branch represents a snapshot of the project's code at a specific point in time. The concept of branching is central to Git and enables collaborative and organized development workflows.

In Git, the terms "main" and "master" are used interchangeably to refer to the primary branch of a repository. However, there has been a shift in the naming convention to promote more **inclusive language**. As a result, many projects and platforms, including Git itself, have started using "main" as the default branch name instead of "master."

The **main difference** between the "**Main**" branch and the **"Master"** branch is essentially the name itself. Functionally, they serve the same purpose: to represent the primary branch where the stable and production-ready version of the project is located.

### **Task 1: Set your user name and email address, which will be associated with your commits.**

If you want to set your username and email address for Git commits, you can do so on your local machine using Git's configuration commands. Open a terminal or command prompt and run the following commands, replacing "Your Name" and "[**your@email.com**](mailto:your@email.com)" with your desired username and email address:

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1690740072375/7a797526-6938-4a4a-9e56-dff9b48d68d5.png align="center")

### **Task 2:**

➡️**Create a repository named "Devops" on GitHub**

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1690740344020/0ea6dc30-46ee-420f-9904-8cc7f8290d78.png align="center")

* ➡️**Create a new file in Devops/Git/Day-02.txt & add some content to it**
    
    ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1690741155010/569b814d-07ad-4ea1-a261-2e590a154f80.png align="center")
    
    ➡️**Connect your local repository to the repository on GitHub.**
    

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1690741015040/567c06af-c508-4eb9-bbde-f34c00251cae.png align="center")

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1690741448909/6975d46d-8581-405e-b43e-cb5e77beed00.png align="center")

➡️**Push your local commits to the repository on GitHub**

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1690743534856/edd338c0-c2fb-4dfe-8c1e-87480d74b9f8.png align="center")

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1690743567279/962cb1a3-f6dd-4412-b83f-eaf72fb5440f.png align="center")

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1690743612536/edd9d56c-1d76-43b9-99c4-f627d9ee786e.png align="center")

➡️**Now we are using the push command to send our local file to GitHub.**

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1690743645891/f99a2905-9408-4b9d-8728-d594faa485c0.png align="center")

➡️**We can see the file which we created locally has been pushed to Github**.

### **🔁Conclusion:**

In conclusion, in this blog, we have learned the following topics about Git and GitHub for DevOps Engineers:

1. Git: A distributed version control system that tracks code changes, facilitates collaboration, and ensures code integrity.
    
2. GitHub: A web-based hosting platform for Git repositories, enabling seamless code sharing and team collaboration.
    
3. Branching: The use of branches in Git to work on separate features independently before merging them back into the main codebase.
    

Throughout the blog, we have covered essential commands and concepts, including:

* Initializing a Git repository
    
* Making commits
    
* Creating branches
    
* Setting up a remote repository
    
* Cloning repositories
    
* Pushing and pulling changes
    

By understanding and mastering these topics and commands, DevOps Engineers can optimize their development processes, maintain organized codebases, and collaborate effectively with their teams.

Embrace these tools to elevate your DevOps practices and drive successful software development projects. Happy coding! 🚀🔧