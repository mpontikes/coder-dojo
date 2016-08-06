# Git with it!
These are some instructions on how to use Git in the command line. Already know the command line? Skip to "Gitting Started".

## Command Line Basics
- cd <file name> : Go to a folder in your computer!
- cd .. : Go back a folder.
- pwd : See the folder that you are in!
- mkdir : Create a folder

## Gitting Started
If this is your first time using Git, type git into the command line. Follow the instructions. If you have a Windows computer you need to [install this](https://git-scm.com/). If you see a help doc come up, you already have Git!

1. Type in the command line "git init" in the folder you want to upload to Github
2. Create a Git repository! Do this on Github.com. Make an account if you don't have one already.
3. Find your git link! Click on clone or download to get it. For example, mine is https://github.com/mpontikes/mpontikes.github.io.git.
4. Type "git branch origin <git link>".
5. Great! Now type git pull origin master.
6. You got some files! 
7. Now time to make youself known! Type "git config --global user.email <YOUR EMAIL ADDRESS> and git config --global user.username <YOUR USERNAME>" so Git knows who you are!


## Uploading Files

1. Type "git add <files you want to change>" in the command line to add files to the commit. (Tip: Use "git add ." to add all files)
2. Type "git commit -m <your message> to save the commit. Make sure the message describes your changes.
3. Type "git push origin master" to upload your files!
4. Follow the instructions!

## Downloading Changes

1. Type "git pull origin master". That's it! BUT BE WARNED!!! If your don't commit your changes, they will be LOST!
