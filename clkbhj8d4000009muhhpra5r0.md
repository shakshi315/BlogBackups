---
title: "Day 3 Task: 🖥️ Linux Command: Conquer the Terminal with Basic Commands for File Magic, Permissions, and Comparison!"
seoTitle: "Linux commands"
datePublished: Thu Jul 20 2023 18:27:51 GMT+0000 (Coordinated Universal Time)
cuid: clkbhj8d4000009muhhpra5r0
slug: day-3-task-linux-command-conquer-the-terminal-with-basic-commands-for-file-magic-permissions-and-comparison
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1689877554634/f7930508-fcb7-4dfa-a5db-7740bf3a13df.jpeg
tags: linux, command-line, learning-journey, linux-for-beginners, linuxpermissions-userpermissions-filepermissions-directorypermissions-linuxsecurity-accesscontrol-setuid-setgid-stickybit-linuxuseraccounts-ownershipandpermissions-linuxfilesystem-commandline-linuxadministration-systemsecurity

---

**1\. To view what's written in a file:**

**cat filename  
**In Linux, the **cat** command is a simple yet powerful tool that allows you to view the contents of a file directly in the terminal. Whether you want to read a configuration file, check the contents of a log file, or simply view a text file's content, **cat** has got you covered.

Example: **cat fruits.txt**

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1689877173162/c5d16980-8c69-4dd3-a655-c460a38024bf.png align="center")

**2\. To change the access permissions of files:**

In the Linux operating system, managing file permissions is essential for controlling access to files and ensuring security. The "chmod" command, which stands for "change mode," allows users to modify file permissions effectively.

Command: **chmod permissions filename**

Example: **chmod 755** [**script. sh**](http://script.sh)

**File Permissions in Linux:**

Each file in Linux has three types of permissions: read (r), write (w), and execute (x). These permissions can be assigned to three different user categories:

1. **The owner (u):** The user who created the file.
    
2. **Group (g):** A set of users who share common permissions.
    
3. **Others (o):** All users who are not the owner or part of the group.
    

**Granting Permissions:**

To grant specific permissions to a file, use the "+" symbol followed by the permission letter. For example:

To grant read, write, and execute permissions to the file owner:**  
chmod u+rwx example.txt  
**In this example, we are granting read (r), write (w), and execute (x) permissions to the file owner (u) for the file "example.txt."    **3.  To check which commands, you have run till now:**

* Command: **history**
    
* Example Output:
    

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1689877129152/5c25968c-0c76-441c-9d0f-a42a83413685.png align="center")

**4. To remove a directory/folder:**

* **Command: rm -r directory name**
    
* **Example: rm -r log**
    
* rm: Stands for "remove," the command used to delete files and directories.
    
* \-r: The flag that indicates a recursive operation, allowing rm to remove directories and their contents.
    
* ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1689877071973/0ce8fd4f-b7b8-4a4d-8f41-68d1c37fd221.png align="center")
    

**5. To create a fruits.txt file and view the content**

               \# **touch fruits.txt**

**6. Add content in fruits.txt (One in each line) - Apple, Mango, Banana, Cherry, Kiwi, Orange, Guava:**

                   # **touch fruits.txt**

                   echo "Apple, Mango, Banana, Cherry, Kiwi, Orange, Guava" &gt; fruits.txt

                 # **cat fruits.txt**  
  
**7**. **To show only the top three fruits from the file:**

* Command: **head -n 3 fruits.txt**
    
* Example Output:
    
    ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1689877218437/4f23b063-a445-47cb-95b4-97da8ec134d8.png align="center")
    

 **8\. To show only the bottom three fruits from the file:**

  Command: **tail -n 3 fruits.txt**

Example Output: **Cherry, Kiwi, Orange, Guava**

 **9. To create another file Colors.txt and view the content:**

**Commands: touch Colors.txt**

**echo -e "Red\\nPink\\nWhite\\nBlack\\nBlue\\nOrange\\nPurple\\nGrey" &gt; Colors.txt**

**cat Colors.txt**

 **10. To find the difference between fruits.txt and Colors.txt file:**

**Command: diff fruits.txt Colors.txt**

**Example Output (if files are different):**

**1c1**

**&lt; Apple, Mango, Banana, Cherry, Kiwi, Orange, Guava**

**\---**

**\&gt; Red, Pink, White, Black, Blue, Orange, Purple, Grey**

The output of the `diff` command will show the lines that are different between the two files. If there are no differences, the command will produce no output, indicating that the files are identical.

#  Conclusion:

In this blog, we've explored some of the basic Linux commands that form the foundation of everyday tasks in the command-line environment. By mastering commands like `ls`, `cd`, `pwd`, and `mkdir`, you can effortlessly navigate and create directories.

Learning how to view file content using `cat` and modifying access permissions with `chmod` empowers you to manage files securely and efficiently.

We've also seen how to compare files with `diff`, making it easier to identify differences between two text files and streamline your file management process.

Remember, practice makes perfect, so don't hesitate to experiment with these commands in your Linux environment. The more you use them, the more confident and proficient you'll become.

Thank you for joining us on this Linux journey! We hope you found this blog helpful in getting started with basic Linux commands. Feel free to share this knowledge with others and continue exploring the vast possibilities that Linux has to offer. Happy Linux-ing! 🐧🌟