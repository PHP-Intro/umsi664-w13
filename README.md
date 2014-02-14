 Github
==========================

This is a starting point to talk about git and github 

Install git
-----------

* [Macintosh](http://git-scm.com/download/mac)

* [Windows](http://msysgit.github.com/) - Note that when you install, 
  I recommend you choose *Run Git From Windows Command Prompt* rather
  than *Use Git Bash only*. 
  (<a href="00-images/01-windows-install.png" target="_blank">Image</a>)

Make a github Account
---------------------

To save time in class make a github account before you come to class to 
particpate in the in-class git activity.

Our Google Doc for Github Names
-------------------------------

<a href="https://docs.google.com/document/d/1mMoH_u1vK32IXXTiXGfTAZPCoBRZUGzpScIiR2_kvgo/edit?usp=sharing" target="_new">Google Doc</a>


Configure Global Git Settings
-----------------------------

    $ git config --global user.name "John Doe"

    $ git config --global user.email johndoe@example.com

Use the -m on the git commits
-----------------------------

    $ git commit -a -m "My commit message"

Otherwise you will need a editor configured - we can skip that for now

In-Class Goals
--------------

* Install git
* Make an empty folder somewhere
* Open Terminal or Command Line and navigate to the empty folder
* Do a "git clone https://github.com/PHP-Intro/umsiX64-ttt.git" to clone 
the class repo
* Go into the course folder "umsiX64-ttt.git"
* Do a "git pull" to get new information
* Make a github account
* Star the class repo from your github account
* Be added as a collaborator to the class github
* Make a folder, add a file to the folder
* Do a "git add foldername
* Do a "git commit -m 'Message'" foder name
* Do a "git status"
* Do a "git push"  (May require a few "git pulls")

If you find yourself being asked to Merge in a text editor  when you 
do a "git pull" - save the file and let the merge happen.   
If you are on a Mac and find yourself looking at a screen full of 
tildes you are in an editor called "vim" type the key sequence ":wq" and Return
to save the file

Here are some resources
-----------------------

<a href="http://rogerdudler.github.com/git-guide/files/git_cheat_sheet.pdf" target="_new">Simple Cheat Sheet</a>

<a href="http://git-scm.com/video/what-is-version-control" target="_new">Video: What Is Version Control</a>

<a href="http://git-scm.com/video/what-is-git" target="_new">Video: What is GIT?</a>

<a href="http://git-scm.com/book/en/Distributed-Git-Distributed-Workflows" target="_new">GIT Workflows</a>


