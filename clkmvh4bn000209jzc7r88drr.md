---
title: "Day 8 - Basic Git & GitHub for DevOps Engineers"
seoTitle: "Git and GitHub"
datePublished: Fri Jul 28 2023 17:43:35 GMT+0000 (Coordinated Universal Time)
cuid: clkmvh4bn000209jzc7r88drr
slug: day-8-basic-git-github-for-devops-engineers
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1690566138158/d7ac7fd9-096b-427a-a120-ef851f259259.png
ogImage: https://cdn.hashnode.com/res/hashnode/image/upload/v1690566198719/ffe5e5a7-04e0-41ef-a3ea-8b6cfc410fce.png
tags: github, version-control, git, distributed-system, devops-journey

---

**Introduction**

Welcome to Day 8 of the #90DaysOfDevOps challenge! Today, we'll explore the magic of Git and GitHub, unleashing the power of version control in software development. Discover the wonders of distributed version control and its advantages over centralized systems. Get hands-on with installing Git, creating a GitHub account, and mastering repository creation and cloning. Let's level up your DevOps journey with Git and GitHub! 🚀🌟💻🐙

### What is Git?

Git is a 🔄 distributed version control system that enables developers to monitor and oversee code changes throughout the software development process. Imagine Git as a 💾 time machine that allows you to save snapshots of your project at different points in time. These snapshots act as checkpoints, making it possible to revisit previous states, investigate code history, and revert to earlier versions if needed.  
With Git, collaboration and code management become more efficient and streamlined.

### What is GitHub?

GitHub is a dynamic web-based platform that fosters developer collaboration, making coding projects an exciting team effort. Its user-friendly interface enables developers to store, share, and effortlessly track code changes, revolutionizing the way software development is done.

***Features of GitHub:***

🗂️ **Code Repositories:** Organize your code and project files in repositories, like virtual folders that keep everything in order.

👥 **Collaboration**: Multiple developers can work together by cloning the repository, making changes, and pushing them back to GitHub.

🔀📜 **Version Control**: GitHub's powerful "Git" system tracks code changes, allowing you to roll back to earlier versions and identify who made which updates.

📝✉️ **Issues and Pull Requests**: Communicate and solve problems effectively by reporting issues and suggesting changes through pull requests.

🌐🤝 **Community and Learning**: Beyond code sharing, GitHub is a vibrant community. Discover, learn, and collaborate on exciting open-source projects with fellow developers worldwide.

## What is Version Control? How many types of version controls do we have?

***Version Control***: 🔄🐙

Version control is like a time machine for code. It helps developers keep track of changes they make to their code as they work on projects. This way, they can easily go back to previous versions if needed and collaborate with others without any hassle.

***Types of Version Control:***

1. **Centralized Version Control (CVC):** 🎯 Centralized version control has a single central repository that holds all the code versions. Developers must connect to this central repository to access and make changes to the code. It's like a hub where all the changes are managed.
    
2. **Distributed Version Control (DVC):** 🌐 Distributed version control gives each developer a complete copy of the code repository, including its full history. This means developers can work independently, create new versions, and collaborate seamlessly without relying on a central hub.
    

### Task 1: Install Git:

**Key Points for Installing Git:**

1. Begin your cosmic coding journey by visiting the official Git website ([https://git-scm.com/](https://git-scm.com/)) and downloading Git tailored for your operating system.
    
2. Embark on the interstellar installation process, guided by the wizard, and enjoy the flexibility to customize settings as you desire.
    
3. Harness the power of visual navigation by opting for the optional Git GUI to elevate your coding experience.
    
4. Confirm your successful installation by typing "git --version" in the terminal, and embrace your newfound cosmic coding prowess.
    
5. As you venture into the cosmos of collaborative coding, 'git' your username and email to claim your cosmic contributions across the universe. 🌌🚀
    

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1690563396490/86027663-efb1-4a13-8b44-f2b692f35fea.png align="center")

### T**ask 2: Create a GitHub Account:**

**Step 1**: Access the GitHub Website Navigate to the official GitHub website ([https://github.com/](https://github.com/)) using your web browser.

*Step 2:*\*\* Sign Up Click on the "Sign Up" button on the GitHub homepage to initiate the registration process.

**Step 3**: Provide Account Information Enter your desired username, a valid email address, and a strong, unique password to create your GitHub account.

**Step 4**: Verify Your Email Check your email inbox for a verification message from GitHub. Click on the verification link provided in the email to confirm your account.

**Step 5**: Choose Your Plan (Optional) GitHub offers both free and paid plans with varying features. Choose the plan that best suits your needs or continue with the free plan.

**Step 6**: Complete Your Profile (Optional) Enhance your GitHub presence by adding profile information, a profile picture, and any relevant details to introduce yourself to the GitHub community.

**Step 7**: Get Started Once your account is verified and your profile is set up, you can start exploring repositories, creating your projects, collaborating with others, and contributing to open-source projects.

***Congratulations!*** You've successfully created your GitHub account and are now part of the world's largest community of developers and coders. Happy coding! 🌟🚀

### 1: Create a New Repository on GitHub

Sign in to your GitHub account.

1. Click the "+" sign and select "New Repository."
    
2. Name your repository and add an optional description.
    
3. Choose the visibility (public or private).
    
4. Optionally, initialize with a README file and choose a license.
    
5. Click "Create repository."
    

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1690564406458/ee3fdb38-952f-49c6-a969-d4aea6edc976.png align="center")

You're all set! Your new repository is now created on GitHub. 🚀🌟

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1690564503554/524256ac-693a-4e20-b395-07cacaa941de.png align="center")

### 2: Clone the Repository to Your Local Machine

1. Open Git Bash (Windows) or Terminal (macOS/Linux).
    
2. Navigate to the directory where you want to clone the repository using the 'cd' command.
    
3. Copy the repository's URL from GitHub.
    
4. In the terminal, type 'git clone' followed by the repository URL.
    
5. Press Enter, and Git will clone the repository to your local machine.
    

Done! You have successfully cloned the repository to your local machine. 📂🚀

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1690564753389/b16b1b0c-ae28-44ad-9393-9a7d1028eee5.png align="center")

### 3: Make Changes, Commit, and Push

Now that you've successfully cloned the repository to your computer, it's time to roll up your sleeves and start editing. Do these steps:

**Move to the directory:**

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1690565013736/c3f4c968-9d49-4dbf-9890-f0a37527bcc0.png align="center")

**Create the file and then check the git status this will show the changes we have made:**

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1690565216020/f8a949f2-b5f9-41f2-9a30-f68c8a966010.png align="center")

**Check Status:** First, run `git status` to see the changes you've made and the files that are ready to be committed.

1. **Stage Changes:** Use `git add` to stage the changes you want to include in the commit. For example, to stage all changes, use `git add .`, or to stage-specific files, use `git add file1 file2`.
    
2. **Commit Changes:** Once the changes are staged, commit them with a descriptive message using `git commit -m "Your commit message here"`. Your commit message should briefly explain the changes you made.
    
3. **Push Changes (Optional):** If you're working with a remote repository (like GitHub), you can push your committed changes using `git push`. This sends your changes to the remote repository for others to see.
    

Remember, committing changes is like taking a snapshot of your project, allowing you to track and manage the history of your code over time. Happy coding! 🚀📝

In day8 of #90DaysOfDevOps challenge, we explored the magic of Git and GitHub. Git empowered us with version control, while GitHub provided a collaborative space. We installed Git, created accounts, and learned to manage repositories. Now, let's soar together in the coding galaxies! 🚀🌟

**Thank you for taking the time to read the blog.**  
**Feel free to share!**  
**Until the next blog, happy learning! :)**