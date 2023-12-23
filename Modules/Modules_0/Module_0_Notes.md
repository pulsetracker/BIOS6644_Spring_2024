# Module 0 (≈2 weeks)  

Computing Environment Setup & Python Refresher  
- Anaconda, Git, & VSCode  
- Python Refresher in Jupyter Notebooks

1) For this course, Jupyter Notebooks are the primary way of communicating results.  "Kernels" are available for Python, R, and many other languages.   
2) Python is the industry standard language for wrangling data of all types.   If you don't know Python, it is strongly recommended that you learn it over this semester.  If you are likely to EVER wrangle data again, it's worth the time invested.
3) Git is the industry standard tool for distributed version control.  It's kind of painful to use, but that's because it enforces rigor for updates and changes.   We'll use git for submitting work.  The workflow you learn doing this will be a good basis for future collaboration.
---

- [ ] <--That kind of checkbox indicates a task you should accomplish

## Setup Github
- [ ] If you don't already have a [gituhub](www.github.com) account, make one.   
- [ ] Send your github username to the instructor via canvas message 
- [ ] If you're not familiar with Github, watch one of the tutorials such as [this one](https://www.youtube.com/watch?v=tRZGeaHPoaw).
- [ ] Clone the class git repo on to the computer you'll use for this course.
> \> git clone git@github.com:pulsetracker/BIOS6644_Spring_2024.git

- [ ] Make a branch with your username, and check it out (activate it)
> \> git branch James_King
>
> \> git checkout James_King 

For the duration of this course, you should always work within this branch (You won't have a reason to alter *main*)

- [ ] Set the branch with your name as the github default for you
> \> git push --set-upstream origin James_King

This makes it so that anytime you add anything, it goes into the branch with your name.  That prevents us from stepping on each other's files.

- [ ] Make a folder inside the Students directory.  This will be where you'll submit work.
> \> cd students
> 
> \> mkdir JamesKing

## Saving & Sending Your Work

Assignments will often be submitted via github.    For practice, write a brief biography about yourself similar to mine (found in BIOS6644_Spring_2024/students/James_King/Module_0/James_bio.txt)
* Note: this file will be visible to everyone on the interwebs.  Don't include anything sensitive.  

- [ ] In your folder under students, make a folder called Module_0
> \> mkdir Module_0

- [ ] In put your biography in the Module_0 folder
> \> mv /path/to/Yourname_bio.txt BIOS6644_Spring_2024/students/James_King/Module_0

- [ ] Commit the change
> \> git add .
> 
> \> git commit -m"Added a biography"

- [ ] Push the commit to github
> \> git push

## Pulling Updates
Course files might be distributed within github.  To get the latest of everything, run a git pull, then merge the main branch into yours.
> \> git pull origin main:main # pulls current main and merges main into your branch
>
> \> git push # Push your branch's updates (the stuff grabbed from main) into GitHub
 
- [ ] Do the pull above
