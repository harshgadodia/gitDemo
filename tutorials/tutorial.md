This tutorial is designed for those interested in learning the basics of git. It aims to introduce, and then reinforce the basics of version control using git. Googling and reading up more is required by design.

But first, a short history of version control:
https://git-scm.com/book/en/v2/Getting-Started-A-Short-History-of-Git

Recommended Resources:

https://www.atlassian.com/git/tutorials
gitexplorer.com
https://guides.github.com/activities/hello-world/

GUI:

You can choose to use a GUI or a CLI (terminal, command prompt, etc). A GUI can be useful to help visualise branches and commit history, but everything a GUI does can be done using command line. I recommend using the command line as far as possible because it is more precise and "pure", but you can choose to checkout (free) GUIs such as Sourcetree and GitKraken.

Basic commands you should know [Any more to recommend?]:

git init  
git add [filename]  
git add .  
git commit -m "message here"  
git push  
git pull  
git merge  
git log   
git status   
git checkout [branch name]  
git checkout -b "new branch name"  
git fetch (what is the difference between fetch and merge)  

Steps to try out:

#1. Create a new repo locally, push to remote

Add new tutorial file to your project to make your life easier.

a. Create new git repository  
b. Check out a new branch. Call it "dev".  
c. Add a readme file in markdown format  
d. Add 100 lines of text to readme file  
e. Commit changes [Your commit message should be concise and helpful]  
f. Push to remote [Do you face any issues? How do you solve them?]  
g. Merge **dev** *into* **master** [How do do you do this? Hint: It is a combination of multiple commands]  

#2. Simulate a merge conflict  

a. Check out dev  
b. Change line 1 of readme file in dev  
c. Check out master  
d. Change line 1 of readme file in master  
e. Merge dev into master [What happens? How should you deal with it?]  

#3 Revisit a previous commit 

a. Check out dev  
b. Revisit your project as of 1 commit ago.  
c. You now realise you rather have your project back at this state. Set it back at this state. How do you do this?  

#4 Collaborating

We are going to work together on making this tutorial even better! Let's do it together while honing our collaborative skills.











