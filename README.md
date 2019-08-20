# Computer Apps II Workflows
---

## Logging In to AWS

1) Go to the AWS Educate website to log into your account -[Click Here](http://awseducate.com)
2) Click on Login to AWS Educate (it's the white text _below_ the yellow button)
3) Click on 'Classrooms' in the upper-right corner
4) Click the blue 'Go To Classrooms' button
5) Click the blue 'AWS Console' button
6) Click 'Cloud9' under 'Recently Visited Services'
7) Click Open IDE

The next screen may look gray as it says "EC2 Instance has stopped. Attempting to wake instance..."

**Check Yourself!** You should be on a screen with a terminal at the bottom that says `vocstartsoft:~/environment $`

## Cloning a Repository

1) Go to the github repository you want to clone. You probably got the link from a link from our class website.

2) In the AWS terminal, type `git clone [website]`

3) In the AWS terminal, change directories into the folder you just created using `cd [name-of-folder]`. The folder name should be the same as the last part of the repository

**Check Yourself**: Your terminal should now say (master) before the dollar sign. For example:

`vocstartsoft:~/environment/example-project `**`(master)`**` $`

## Making Changes

This is where you will edit your code. You can open files using the AWS folders on the left side of the screen, or by using commands in the linux terminal:

`touch [file-name]`: creates a new file called `[file-name]`. **Don't forget to include an extension**, like .txt or .html

`c9 [file-name]`: opens a file in the Cloud9 editing window

`mkdir [folder-name]`: makes a new folder called `[folder-name]`

## Committing Changes

The following 3 commands will save your work back to the public GitHub repository:

`git add *`: prepares all of the files in your directory to be uploaded
`git commit -m "[message]"`: commits all of your changes with a message detailing the changes you made
`git push origin master`: uploads the files to the GitHub Repository
