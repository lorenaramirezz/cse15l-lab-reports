
# Installing VSCode

If VScode is not already installed on your computer, here is the link: [Link] https://code.visualstudio.com/

There are instructions for downloading and installing VSCode on your computer. I already had it installed so I was able to skip this step for today! 
As you know, there are different versions to install for macOS and Windows so make sure you follow the right directions for the one that works for you!

My page might look a bit different than yours if you just installed it but no worries.

![VS Code](Screen Shot 2023-04-06 at 12.29.28 PM.PNG)

# CSE15L account
Prior to remotely connecting, I had to set my password for my course-specific account on ieng6. 
You can look up your course-specific account for CSE 15L here: https://sdacs.ucsd.edu/~icc/index.php
I had to reset my password prior to connecting to this remote server. 
This tutorial explains this process of resseting your password well: https://drive.google.com/file/d/17IDZn8Qq7Q0RkYMxdiIR0o6HJ3B5YqSW/view?usp=share_link

# Remotely Connecting
Now at this point I had some trouble connecting to a remote server but as of now it seems to be working again. In VScode you want to open up the terminal, you can do this by going to Terminal --> New Terminal.
In this terminal you want to type the following:

<img width="777" alt="Screen Shot 2023-04-10 at 2 10 36 PM" src="https://user-images.githubusercontent.com/130100480/230999582-47f90641-d5cb-4a73-9378-703afa77fbcd.png">

`$ ssh cs15lsp23zz@ieng6.ucsd.edu`
Note that you don't need to type the $, but everything after that.
You will have to replace the letters 'zz' with the 2 letters in your course-specific username.

Once you enter this, the following will occur if this is your first time connecting to this server.
`⤇ ssh cs15lsp23zz@ieng6.ucsd.edu
The authenticity of host 'ieng6.ucsd.edu (128.54.70.227)' can't be established.
RSA key fingerprint is SHA256:ksruYwhnYH+sySHnHAtLUHngrPEyZTDl/1x99wUQcec.
Are you sure you want to continue connecting (yes/no/[fingerprint])? `

Type in yes and hit enter, it should then ask for your password. 
Type in your password and hit enter once again. 

`Last login: Sun Jan  2 14:03:05 2022 from 107-217-10-235.lightspeed.sndgca.sbcglobal.net
quota: No filesystem specified.
Hello cs15lsp23zz, you are currently logged into ieng6-203.ucsd.edu

You are using 0% CPU on this system

Cluster Status 
Hostname     Time    #Users  Load  Averages  
ieng6-201   23:25:01   0  0.08,  0.17,  0.11
ieng6-202   23:25:01   1  0.09,  0.15,  0.11
ieng6-203   23:25:01   1  0.08,  0.15,  0.11

Sun Jan 02, 2022 11:28pm - Prepping cs15lsp23`

Now this means that the terminal is now connected to a computer in the CSE basement.

