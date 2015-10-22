# GitHub Tutorial

_By Giovanni Morales_

---
## Git vs. GitHub
Git is a version control system that allows the user to edit a file and save by creating snapshots so you can go back to past screenshots later.
Git is also used for working with others to work on the same project at the same time.
Github is the website that allows people to see other people's projects and contribute to them. 

---
## Initial Setup
1. One one tab make a github account on [github.com](https://github.com)
2. On the top right coner of the page click on the profile icon 
3. On the left sidebar click SSH keys, then add SSH keys
4. On another tab go to [c9.io](https://c9.io)and sign in using github (the cat icon) and create a workspace
5. Go to the dashboard by clicking the "CLoud9" buuton
6. Click SSH keys and copy the ssh-rsa... 
7. Go back to github and paste what you just copied 
5. in the commaand line type git config user.name "First name Last name" 
6. then do git config user.email "whatever@something.com"
7. Type "ssh-T git@github.com" in the command line, after type yes


---
## Repository Setup

1.When you're in the directory you want to be in do git init  
2.When you want to add something to be saved you do git add "file name"  
3.When you want to save what you added you do git commit -u origin master only the first time and every other time you just put git init

---
## Workflow & Commands

#### Commands
git init - allows the use of git  
git add - adds files to the "stage"    
git status - lets you know which files need to be added to the stage and files that are already on the stage  
git commit - takes a snapshot or save of whatever is on the stage  
git push - takes commit and sends it to github to be stored there (a remote)  

#### Workflow
The workflow of git is to edit a your files or directories and then git add, git commit, git push so all your edits are shown on github. 

---
## Collaboration

The way collaboration works on github is through forking and cloning. So on github.com you can look at someone's project but you can also fork it to make your own remote. from there you clone it by doing git clone and pasting the git clone url on github. from there you can add, commit push but it won't be on the original project. so you do a pull request to see if original creator likes your edits and put it on their own project
