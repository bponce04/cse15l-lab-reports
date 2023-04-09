# CSE 15L: Logging into your CSE 15L ieng6 account 

## Intro:

Hello! My name is Brian Ponce and I am a Mathematics-Computer Science (MA30) major from Warren College (go Bearls!). 

In this lab report, I will be going over the following:

* How to reset your CSE 15L Spring 2023 UCSD account password
* Installing Bash and VS-Code and how you can use both to log into your ieng6 account

## Step 1: Resetting your CSE 15L Account Password

What most incoming CSE 15L students don't know is that you have a specific UCSD Account for this course. To reset your account password you must procede with the following:

1) To access this username, you must go to the [Account-look up page](https://sdacs.ucsd.edu/~icc/index.php) and sign in with your UCSD AD username (e.g brponce) and your PID (e.g A12345678).

2) After you log-in, you should be able to see your CSE 15L account username below the subheading **Additional Accounts.** By clicking on your CSE 15L account username, you will be directed to another page, in which it will ask you to change your global password at the near top of the page. 

3) Once you request to change your global password, an e-mail will be sent to your UCSD gmail account, where you will then be directed to a page where you will enter your new password. **Be sure to follow the website's guidelines in making your new password.**

4) After you successfully reset the password to your CSE 15L account, wait for about 15 to 60 minutes for your account's password to be updated.

For any trouble with following these procedures, a visual step-by-step [guide](https://drive.google.com/file/d/1nlkyhMfsk2-grubXb6d4jC4ftWhQyJyh/view?usp=sharing) created by the CSE 15L team is avaiable to guide you through out this process.

![ImageOne](https://raw.githubusercontent.com/bponce04/cse15l-lab-reports/main/Account%20Lookup.png)

## Step 2: Setting up Visual Studio Code and Git (Bash)

Once you are done resetting the password to your CSE 15L account, you must then set up the programs Visual Studio Code and Git so that we are able to log-in to your ieng6 account.

1) Download Visual Studio Code [here](https://code.visualstudio.com/download) and Git (Bash) [here](https://gitforwindows.org/). You will be using both Visual Studio Code and Git (Bash) to log-in to your ieng6 account into a remote server.

2) To use Git's Bash terminal, use the Crtl+Shift+P Visual Studio code shortcut to open a settings menu at the top of the program window. After doing so, then type in "Select Default Profile," where you must choose Git Bash to be your default terminal. Doing so will set Git Bash as your default terminal when opening a new terminal in Visual Studio Code.

![ImageTwo]([tps://raw.githubusercontent.com/bponce04/cse15l-lab-reports/main/Select%20Default%20Profile.png)
## Step 3: Getting Into The Remote Server (SSH)

Once you have Visual Studio Code and Git Bash set up, it is finally time to log in to your ieng6 account. 
  
1) Open up a new terminal in Visual Studio Code (either with Crtl + Shift + ' or by selecting 'New Terminal' in the Terminal bar). Make sure that you have Git Bash as your default terminal. If not, look at the second sub-step in Step 2.
  
3) Once you have the Git-Bash terminal open in Visual Studio Code, type in the following command: `ssh`, with your CSE 15L account username afterwards with the address `ieng6.ucsd.edu`. Your input at this point should like this: `ssh cs15lsp23<insert your unique 2 characters here>@ieng6.ucsd.edu`. You will then recieve a message asking if you want to continue the connection. Make sure to type in `yes` to proceed. After typing in yes, you will asked to type in your **new** CSE 15L account password 

*Note: Your password will not be visible when you type it in*.

![ImageThree](https://raw.githubusercontent.com/bponce04/cse15l-lab-reports/main/Connection%20Prompt.png)

Afterwards, you should see this message indicating that you were able to log in to your ieng6 account. 

*Note: If you were not able to log in to your ieng6 account, make sure that you: 1. typed in your password correctly, 2. you typed in ieng6.ucsd.edu, 3. you copy and pasted your CSE 15L account password without any spaces before/after your actual password.*
  
4)









