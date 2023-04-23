**# Lab Report 1**
---
## Installing VS Code
1. Go to this link:[Link]( https://code.visualstudio.com/) and install **Visual Studio Code** onto your computer following the instructions.(Whatever your operating system is, download that specific version such as macOS for mac or Windows for pc).
2. After downloading Visual Studio Code onto your computer open up a page that should look like the one shown here. 
<img width="1440" alt="Screen Shot 2023-04-06 at 4 20 40 PM" src="https://user-images.githubusercontent.com/130112383/231018364-0eb6d7ad-bb6f-4a4f-afbb-73338c39de7c.png">


## Remotely Connecting
1. When you get to that page open up the terminal and write ssh and add cs15lsp23zz@ieng6.ucsd.edu(for the 2 z's change it to your course-specific account)
`ssh cs15lsp23zz@ieng6.ucsd.edu`

```
The authenticity of host 'ieng6.ucsd.edu (128.54.70.227)' can't be established.
RSA key fingerprint is SHA256:ksruYwhnYH+sySHnHAtLUHngrPEyZTDl/1x99wUQcec.
Are you sure you want to continue connecting (yes/no/[fingerprint])? 
```
2. After getting this message plug in yes and you should get an option to plug in your password. You should be connected to the server afterwards.
<img width="1440" alt="Screen Shot 2023-04-10 at 4 32 38 PM" src="https://user-images.githubusercontent.com/130112383/231018679-56ea8715-1875-48b8-8ea1-7d9718039a57.png">


## Trying Some Commands
1. For this part try to plug in some commands such as this:
- `pwd`, `cd`, `cp`, `ls`, `mkdir`

**Explanation of each command**
- `pwd` this command writes out the full path name of the current directory
- `cd` this command is known as change directory and  is used to change the current working directory
- `cp` this command allows you to copy your files or directories
- `ls` this command is used to list files and directories
- `mkdir` creates a new directory
- hint: The directory "." refers to the working directory and ".." refers to its parent directory

<img width="1440" alt="Screen Shot 2023-04-10 at 12 37 35 PM" src="https://user-images.githubusercontent.com/130112383/231018724-d2aa4bc9-eb68-49c4-9ee7-f5ec6ca78b20.png">

2. In this image there have been multiple commands that I have used. 
- first I have used `pwd` to show my current directory
- then I put `cp /home/linux/ieng6/cs15lsp23/public/hello.txt~/`, and after `ls -a`, which shows hidden files
- I tried the same thing but changed to `ls -lat`, the 'l' stands for long format, 'a' stands for hidden files and the 't' stands for sort list
- I then wanted to create a new directory so I used `mkdir` and typed folder000, next used `cd folder000` to change the directory
- To see if it works I used `pwd` to show the new current directory
- To delete the changes I put `cd ..` then `pwd` which shows folder000 deleted


