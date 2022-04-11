# Week 2 Lab Report

## How to Log Into a Course-Specific Account on ieng6.

## 1. Install VSCode

    Download VSCode with this website link: [Install
    VSCode]([Link](http://a.com)). Once you install VSCode, you will open the application and see this.

![Image](installingVscode.png)

## 2. Remotely Connecting

    First, open the VSCode terminal and type: $ ssh cs15lsp22zz@ieng6.ucsd.edu *** (replace the zz with your actual username). If a question pops up, make sure to type 'y' for yes and input your password. You should see something like this:

![Image](remotelyConnecting.png)

## 3. Trying Some Commands

    There are many types of commands you can use like cd, ls, pwd, mkdir, and cp. "ls" shows you what it is in your directory. For example, I used /home/linux/ieng6/cs15lsp22/cs15lsp22abc. In my example, abc was my classmates username and it tells you whether it is a directory or not. 
    
![Image](tryingSomeCommands.png)

## 4. Moving Files over SSH with scp

    If you have a file on your computer and want to transfer it to a remote computer, you will use the command scp. For example, once you have compiled the file on the client server, you will type in your terminal: scp <your file> cs15lsp22zz@ieng6.ucsd.edu:~/

    After, you log in remotely (using ssh and your ieng6 account). When you use ls, you will see that file on the remote server. 

![Image](movingFiles.png)
