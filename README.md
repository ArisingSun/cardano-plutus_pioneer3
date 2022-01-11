# Plutus Pioneer 3

Week 1: 

First Day

learning GitHub And Setting Up Plutus Pioneer for tomorrows Lecture. 

## CD command

example: cd ../test-repo 

this switches the termal to target folder test-repo

## Update Be sure to ctrl save ur work before adding and commiting!

Just learned SSH and setting it up and the .git
After setting up the SSH use command git clone and copy past the ssh id and hit enter to see ur repo from github into the directory your in

to move the terminal into the folder Cardano_plute use : cd Card *TAB* to finish

you'll see main below. to show ur in the main branch. 
also ls -al lists all files and folders in the repo ur in. blue means folders

.git saves all files and folder changes and all history of changes made.

these changes are kept track also from the git website.

## NEXT Git Status command

use git status command

this will give you the status of the branch or main ur on as well as if its up to date. 
but these aren't saved in a commit yet shows all updates and deletions

if example create new folder and index.html and then command git status. This will show untracked files and modifies. 
git doesn't know about this file so you need to track it before you commit. 

## Git Add

You must have git track ur changes before you can commit. 
to do this use the
git add .  Command

This tells git to track all changes made
the "." tells git to track all files.
otherwise type in the files name for git to track like index.html
press enter and command git status again youll see new file is tracked!


## Git Commit command

one all files are tracked then you can commit these files to git
you must type:
git commit -m
-m = message and must be added and must be relavant to what you changed. 
example: git commit -m "Updated README and experimented with HTML file" 
OPTIONAL: you can use -m again to add a description to the end of ur message.

this only is a local commit and isn't live yet.

## git push command

Example: git push
pushes the new local update to the live repository.
youll need to specify what branch you want to push to like origin or main
Example: git push origin main
## SSH INFO

is a secure key to allow ur local machine to connect to ur git hub account. 
u secure a private key and public key.
to learn how to set it up look up more info on youtube. also do not use ctrl C to copy in the terminal as  that means something different.


## Branch Developmet and commands

branch devlopment is a way to develope the same code on a seperate sandbox so to speak in order to not ruin or bug up the main code that is already functional.

Command list
git branch: shows the number of branches as well as what branch you are on with *
git checkout -b *insertbranchname* : breaks out of the current branch and creates a new one.
git checkout *insertexistingbranchname* : switches to named branch.

1. Open index.html in your browser.

to push use git push -u origin feature-readme

## Creating Pull Requests

what is a PR? a request to have code pulled into a nother branch. example putting feature branch into main branch. 