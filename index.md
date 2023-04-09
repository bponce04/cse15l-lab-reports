# CSE 15L: Logging Into Your CSE 15L ieng6 Account 

## Intro and :

Hello! My name is Brian Ponce and I am a Mathematics-Computer Science (MA30) major from Warren College (go Bearls!). 

In this lab report, I will be going over the following:

* How to install and set up Visual Studio Code and Git Bash
* How to connect to a remote server using your ieng6 account
* Using remote server commands (and tring them out!)

*Note: Before starting on the first step, make sure that you have already reset the password to your UCSD CSE 15L account. If not please use the [guide](https://drive.google.com/file/d/17IDZn8Qq7Q0RkYMxdiIR0o6HJ3B5YqSW/view?usp=sharing) by the CSE 15L team to do so.

## Step 1: Setting up Visual Studio Code and Git Bash

After resetting your CSE 15L account password, let's set up the following programs: Visual Studio Code and Git. Setting up these programs will allow us to log-in to our ieng6 accounts.

1) Download Visual Studio Code [here](https://code.visualstudio.com/download) and Git (Bash) [here](https://gitforwindows.org/). You will be using both Visual Studio Code and Git (Bash) to log-in to your ieng6 account into a remote server.

2) To use Git's Bash terminal, use the Crtl+Shift+P Visual Studio code shortcut to open a settings menu at the top of the program window. After doing so, then type in "Select Default Profile," where you must choose Git Bash to be your default terminal. Doing so will set Git Bash as your default terminal when opening a new terminal in Visual Studio Code.

![ImageTwo](https://raw.githubusercontent.com/bponce04/cse15l-lab-reports/main/Select%20Default%20Profile.png)

## Step 2: Getting Into The Remote Server (SSH)

Once you have Visual Studio Code and Git Bash set up, it is finally time to log in to your ieng6 account. 
  
1) Open up a new terminal in Visual Studio Code (either with Crtl + Shift + ' or by selecting 'New Terminal' in the Terminal bar). Make sure that you have Git Bash as your default terminal. If not, look at the second sub-step in Step 2.
  
3) Once you have the Git-Bash terminal open in Visual Studio Code, type in the following command: `ssh`, with your CSE 15L account username afterwards with the address `ieng6.ucsd.edu`. Your input at this point should like this: `ssh cs15lsp23<insert your unique 2 characters here>@ieng6.ucsd.edu`. You will then recieve a message asking if you want to continue the connection. Make sure to type in `yes` to proceed. After typing in yes, you will asked to type in your **new** CSE 15L account password 

*Note: Your password will not be visible when you type it in*.

![ImageThree](https://raw.githubusercontent.com/bponce04/cse15l-lab-reports/main/Connection%20Prompt.png)

Afterwards, you should see this message indicating that you were able to log in to your ieng6 account. 

![ImageFour](https://raw.githubusercontent.com/bponce04/cse15l-lab-reports/main/Successful%20Connection.png)

If everything was successful, then you have officially connected to the remote server with your ieng6 account! 

*Note: If you were not able to log in to your ieng6 account, make sure that you:

* typed in your password correctly. 
* You typed in ieng6.ucsd.edu 
* You copy and pasted your CSE 15L account password without any spaces before/after your actual password.

## Step 3: Using Remote Server Commands


  










