# GitHub Tutorial

_by Roxanne Condello_

---
## Git vs. GitHub
* **Git**
 * Keeps track of code ("Snapshots") A.K.A version control
 * Doesn't require github
 
* **Github**
 * Tracks changes
 * Allows you to pull/clone other peoples code in order to collaborate
 * Stores code and files
 * Needs Git in order to work

 In order to use these commands make a github account [here](https://github.com/) 
---
## Initial Setup
To initialize git in the command line to keep track of your code you use `git init`. 
This is basically telling the command line to have git keep track of the code. 
You can also add your files on the stage by using `git add file.name`. The stage is where 
your files will be shown on Github. 


---
## Repository Setup
A repository is also called _repo_ for short. In order to set a repo up you have to have a file 
called `README.md` so your code could appear on github. This is also stated on the website.
This may be confusing but before you add your repo you have to **make sure you are in the right folder**
if you are not you will add the wrong file, it is very difficult to delete files off of github.
This is also the place where your code will appear on github you will see this on your profile and all of 
your repos are listed for the world to see. 


---
## Workflow & Commands
Workflow- A certain order in code to create the just right effect.
#### _Workflow to push your code_ 
1. `git add file.name`
2. `git commit -m "comment for code"`
3. `git push -u origin master` only once then its `git push`

#### _git commands_
* `git init` - Initializes git 
* `git add`- adds the README.md to the stage
* `git commit -m "comment for code"` - lets github keep track of **_all_** changes
* `git push -u orgin master` - Brings the code up to github for others to use/ see.
* `git push`
* `git clone URL` - clones an exact copy of the code to edit but is **different** from `git pull` 
has more branches to keep track 
* `git status`- shows the commits and files added to the stage
* `git pull` - takes in exact copy of code 


---
## Collaboration 

