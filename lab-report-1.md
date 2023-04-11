
# Installing VSCode

If VScode is not already installed on your computer, here is the link: [VSCode Installation](https://code.visualstudio.com/)

There are instructions for downloading and installing VSCode on your computer. I already had it installed so I was able to skip this step for today! 
As you know, there are different versions to install for macOS and Windows so make sure you follow the right directions for the one that works for you!

My page might look a bit different than yours if you just installed it but no worries.

![VS Code Installation](vscodescreenshot.png)

# CSE15L account
Prior to remotely connecting, I had to set my password for my course-specific account on ieng6. 
You can look up your course-specific account for CSE 15L here: [ieng6](https://sdacs.ucsd.edu/~icc/index.php)

I had to reset my password prior to connecting to this remote server. 
This tutorial explains this process of resetting your password well: [Reset Password Tutorial](https://drive.google.com/file/d/17IDZn8Qq7Q0RkYMxdiIR0o6HJ3B5YqSW/view?usp=share_link)

# Remotely Connecting
In VScode you want to open up the terminal, you can do this by going to Terminal --> New Terminal.
In this terminal you want to type the following:

`$ ssh cs15lsp23zz@ieng6.ucsd.edu`

Note that you don't need to type the $, but everything after that.
You will have to replace the letters 'zz' with the 2 letters in your course-specific username.

Once you enter this, the following will occur if this is your first time connecting to this server.
```
⤇ ssh cs15lsp23zz@ieng6.ucsd.edu
The authenticity of host 'ieng6.ucsd.edu (128.54.70.227)' can't be established.
RSA key fingerprint is SHA256:ksruYwhnYH+sySHnHAtLUHngrPEyZTDl/1x99wUQcec.
Are you sure you want to continue connecting (yes/no/[fingerprint])? 
```

Type in yes and hit enter, it should then ask for your password. 
Type in your password and hit enter once again. 

You should see something similar to the image below. 

![Remotely Connecting](remotelyconnecting.png)

Now this means that the terminal is now connected to a computer in the CSE basement!

Now we can run some of the commands we have learned!

# Running Commands



