## Change++ 2023-2024 Underclassmen pre-recruitment activity

Hi! Thanks for participating and showing interest in Change++. The first thing you need to do is to create a Github account and install git on your local device.

## Purpose

The purpose of this activity is to give you experience working with common developer tools such as Git and package managers. Through completing this activity, you will use the most common git and npm commands. This exercise is meant for students that have completed an intro-level Computer Science course (CS 1101, CS 1104, AP Computer Science, anyone that has dabbled with Python, Javascript, or any other progrmaming language).

If you have already installed or completed these steps in the past, you may skip them here.

## Creating your Github account

[Github](https://github.com)
If you do not already have a Github account, we would advise you to create one using your school email.

## Installing Git

[Git install guide](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
Please follow this guide to install Git on your local device.

## Installing NVM, npm, and Node.js

# macOS
In your `terminal`:
1. `brew update`
2. `brew install nvm`
3. Restart your terminal
4. `nvm install node`
5. `nvm install-latest-npm`

# Windows
[Node install guide on Windows](https://learn.microsoft.com/en-us/windows/dev-environment/javascript/nodejs-on-windows)
Please follow this guide to install Node on your Windows device

# Linux
You got this.

## Now for the actual activity

0. Watch this tutorial on Git and try to understand the commands that you use in this exercise:
[Basics of Git](https://youtu.be/hwP7WQkmECE)
For the purpose of this exercise and your use-case in Change++. You can think of npm and any other package manager you may use as a tool to control the versions of third-party packages/modules/libraries.

1. Please DM `tigerr_` on Discord with your Github email. You will receive an invite within 24hrs.
2. Create a new folder on your device and navigate to that folder using your shell program or your command interpreter.
3. `git clone https://github.com/tiger01tgr/changepp_learn.git`
4. `cd changepp-learn`
5. `git checkout -b {first initial + lastname + dev}`
6. `npm install`
7. `npm run dev` to start the program
8. fix the typo in /src/index.js and change the default introduction text to your own introduction text
9. `git add .`
10. `git commit -m 'my first commit`
11. `git push origin {first initial + lastname + dev}`
12. Congrats! You made your first commit!
13. If you want, try to figure out how to make a pull request in Github (Google it, if you don't know what that means or how to do it).