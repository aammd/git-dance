Git dancin'
========================================================
author: Andrew MacDonald
date: 05 Nov 2013
autosize: TRUE
transition: rotate

git is a distributed version control system
=======================================================
![distrib](branching-illustration@2x.png)

git is also a lot like dancing
=======================================================
<img src="bear.gif" height = 700 width = 700></img> 

You can dance on your own ..
=======================================================

.. or in huge groups
=======================================================

Some people can get very fancy with it
=======================================================

other people are much simpler
=======================================================

But all of us love it
=======================================================
incremental: true
git is a useful tool for
* tracking changes to files
* organizing projects
* **sharing** data and code 

Today: the Basic Step
=======================================================
incremental: true
![rog](mr-rogers.gif)
***
* starting a repo
* making commits
* using remotes

Dancing shoes:
=======================================================
* Rstudio
* git
* git bash (windows)

Start the music!
=======================================================
incremental: true
1. create a new directory 
 * <small> suggestion: not in your desktop </small>
1. open git bash or terminal

=======================================================
incremental: true
```sh
cd path/to/your/directory
```
```git
git init
```

=======================================================
incremental: true
1. open a text editor
 * <small> something simple: notepad, gedit, `nano` </small>
1. write out the title of a project you're working on:

```
# This is my title
```

1. save in your new directory as **README.md**

Back in the command line:
=======================================================
incremental: true

* `git status`
* `git add README.md`
* `git commit -m "adding a readme file"`

Back in the editor:
=======================================================
incremental: true

* add your name
* save
* `git status`
* `git add .`
* `git commit -m "adding my name"`

The Step:
=======================================================
incremental: true

* **work**
* **save**
* `git add .`
* `git commit `
* **work**
* **save**
* `git add .`
* `git commit `

=======================================================
* `git log`
* `git log -p -3`

Technical explanation
=======================================================
![snap](snapshots.png)

Technical explanation
=======================================================
![areas](areas.png)

>**[This is the main thing to remember about Git if you want the rest of your learning process to go smoothly. Git has three main states that your files can reside in: *committed*, *modified*, and *staged*.](http://git-scm.com/book/en/v2/Getting-Started-Git-Basics)**

Other steps (if we have time):
=======================================================
* To the side!
  - `git branch`
* To the back!
  - `git checkout`

Get out on the floor:
=======================================================
Add a remote repository:

* First, go to github and start a repository
* Follow the steps!

```shell
git remote add origin https://github.com/aammd/practice.git
git push -u origin master
```
* [Rstudio buttons greyed out?](http://landeco2point0.wordpress.com/2014/07/22/things-i-forget-pushpull-greyed-out-in-rstudio/)



=======================================================
