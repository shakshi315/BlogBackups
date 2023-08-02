---
title: "Day 4 Task: Basic Linux Shell Scripting for DevOps Engineers."
seoTitle: "Shell Scripting for DevOps Engineer"
datePublished: Fri Jul 21 2023 01:36:42 GMT+0000 (Coordinated Universal Time)
cuid: clkbwuq7v00020al79cn2fdz8
slug: day-4-task-basic-linux-shell-scripting-for-devops-engineers
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1689902744034/1c510a9f-fe7f-44f0-b2c3-e94fe2790028.png
tags: devops, shell, shell-scripting, linux-kernel, binbash

---

# Introduction

Let's Step into the exciting realm of Day 4 in our epic #90DaysOfDevOps adventure! 🚀Embrace the limitless potential of Linux shell scripting and unlock a world of automation and efficiency. Are you ready to conquer the command line and become the architect of streamlined workflows? 🏗️ Let's embark on this captivating journey together, empowering ourselves with the mastery of shell scripting's core principles! 🌟

# What is Kernel?

The kernel is a fundamental part of your computer's operating system. It acts as a bridge between the hardware (the physical parts of your computer) and the software (the programs you use). It handles tasks like memory management, device communication, and process scheduling.

In simpler terms, the kernel is like the hidden hero of your computer. While you may not see it directly, it's always working in the background, making sure that everything on your computer runs efficiently and that your favourite applications can work together without causing any chaos.

# What is Shell?🐚

Imagine your computer as a house, and the shell is like the front door or the entryway to that house. It's the place where you interact with the computer and give it commands to perform various tasks.  
In simple terms, the **shell** is a **special program** that allows you to talk to your computer using text commands. You can type in **instructions**, and the shell will understand what you want and carry out those tasks for you💻.

The shell makes it easier for you to work with your computer because you don't need to click on icons or navigate through menus. Instead, you can type simple, straightforward commands, and the shell will take care of the rest. It's a powerful tool that lets you control your computer more efficiently and get things done faster!

# Shell Scripting for DevOps

Shell scripting for DevOps is like having a secret toolbox. It's a way to create small, powerful scripts that automate tasks and make life easier for DevOps engineers.

With just a few lines of code, they can deploy applications, manage servers, and perform many other tasks, saving time and effort.  
So, in essence, shell scripting for DevOps is like having a powerful spellbook that allows engineers to work magic, making software development and operations faster, more efficient, and more effective! 🚀💻

# What is `#!/bin/bash?`

`#!/bin/bash` is like the secret code that starts the show! 🚀🎬 It's called a "shebang" or "hashbang."  
In simple terms, it's the line that tells your computer to use the "bash" program to understand and execute the rest of the script. It's the key that unleashes the power of shell scripting, allowing you to automate tasks and work wonders with your computer.  
So, whenever you see `#!/bin/bash`, know that exciting things are about to happen in the world of DevOps! 💡💻

# **Can we write** `#!/bin/sh` **as well?**

Yes, you can indeed write `/bin/sh` as a symbolic link to `/bin/bash` if your system allows it and you have the necessary permissions.  
`#!/bin/sh`: This tells the computer to use the default system shell interpreter, which is often linked to the Bourne shell or a compatible shell like Bash or Dash. It ensures that the script will work on most Unix-like systems because `/bin/sh` is typically available on these systems.  
The **key distinction** is that Bash (`/bin/bash`) has more features and capabilities compared to the default POSIX shell (`/bin/sh`).  
When a script is specifically written for Bash and uses **Bash-specific features**, it should use `#!/bin/bash` as the shebang line to ensure proper execution.  
On the other hand, if a script is written to follow **the POSIX shell standard** and does not use any Bash-specific features, it can use `#!/bin/sh`.  
Using `#!/bin/sh` allows the script to be more portable, as it can be executed on various Unix-like systems without relying on the advanced features provided by Bash.

# Write a Shell Script that prints a message

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1689900016877/d669b8e0-0ac9-4db5-9d0f-756dcfa53929.png align="center")

**Let's break down the steps for creating and running the shell script:**

1. **Create a New Script**: Start by creating a new file, like "devops\_scripts.sh," using the nano text editor or any other code editor of your choice.
    
2. **Add Shebang Line**: Include the shebang line `#!/bin/bash` at the beginning of the script. This tells the system to interpret the script using the Bash shell.
    
3. **Write the Script**: In the script, use the `echo` command to print the desired message. For example, you can use the `echo "I am a great DevOps engineer and will complete the #90DaysOfDevOps challenge"`.
    
4. **Save and Exit**: Save the changes made to the script and exit the text editor.
    
5. **Set Execute Permissions**: Use the command `chmod 700 devops_scripts.sh` to give the script executable permissions. This allows you to run the script.
    
    ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1689900745871/00ebc0f2-5873-4120-9902-7339917bc092.png align="left")
    
6. **Run the Script**: Execute the script by typing `./devops_scripts.sh` in the terminal. The message should appear on the terminal when the script is executed.
    

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1689901023645/0208aa90-57f7-4fc5-b26d-fc05d5f3d722.png align="left")

By following these steps, you'll have a simple shell script that displays your message, and you can start your DevOps journey with confidence! 🚀👩‍💻

# Write a Shell Script to take user input, input from arguments and print the variables

In this example, the script uses the `read` command to take user input and store it in variables `user_name` and `favorite_language`. It then prints out personalized messages using the input provided by the user. When you run this script, it will prompt you to enter your name and favourite programming language. After receiving your input, it will respond with customized messages based on the information you provided.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1689901627138/a5d247f4-f821-433a-aa2a-9f33f025c711.png align="center")

# Write an Example of If else in Shell Scripting by comparing 2 numbers

In this script, the user is prompted to enter a number. The script then uses if-else statements to check if the number is positive, negative, or zero.

When you run this script and enter a number, it will display whether the number is positive, negative, or zero based on the user's input.

This simple example demonstrates how if-else statements can be used in shell scripting to make decisions based on conditions.🧮📝🚀

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1689901951841/098bcf34-f220-4b0d-81f0-a6578f0ac8ea.png align="center")

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1689902062022/7c83326b-10eb-4c61-b3af-a93f50f7216d.png align="center")

# **Conclusion**

\-&gt; In this blog, we embarked on an exciting journey into the world of shell scripting for DevOps.  
\-&gt; We started by understanding the power of the `#!/bin/bash` shebang and how it sets the stage for our scripts to perform their magic.  
\-&gt; With the ability to interact with users and handle input, we created scripts that personalized messages and compared numbers.  
\-&gt; These simple yet fundamental concepts gave us a glimpse of the incredible automation and decision-making capabilities that shell scripting offers.

By exploring examples, we unlocked the potential of if-else statements and witnessed how they enable our scripts to make smart decisions based on specific conditions.

So, as we wrap up this blog, I invite you to continue exploring the wonders of shell scripting. Dive deeper into conditional statements, loops, and more!  
\*\*  
Thank you for joining me on this adventure!\*\*  
I hope you enjoyed the notes, and I look forward to having you read more in my blog. **Feel free to share your thoughts,** suggestions, or any specific topics you'd like to delve into next.  
**Keep scripting, and may your DevOps path be filled with success and innovation! 🚀**