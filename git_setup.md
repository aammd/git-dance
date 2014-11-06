---
title: "Git Setup"
author: "Alathea DL"
date: '2014-11-05'
output:
  html_document:
    toc: yes
---

# Windows

## 8+

### Download and Install Git

### Download and Install RStudio

[Get Rstudio here](http://download1.rstudio.org/RStudio-0.98.1087.exe).

# Mac

## Snow Leopard

### Download and Install Git

### Download and Install RStudio

## Troubleshooting

### Cannot find the git directory

* In a terminal, type `which git` to find where Git is installed
* In Finder, go to `Go` and type in the folder you found above
* Drag this folder to `Favorites` (in the left-hand toolbar)
* Now when you browse for git within RStudio, you can access the folder and find the application `git`

### Error r error 4 ...

From [this page](https://support.rstudio.com/hc/communities/public/questions/200764217-new-user-installation-problem-Mac-)

> Typically when we see this problem, it's caused by a
> conflict between multiple versions of R installed on your
> computer. We recommend in this case navigating to the
> folder `/Library/Frameworks/R.framework/Versions/` and
> removing any versions of R that you don't wish to use
> (you can move them to another folder if you think you
> might want to use them later).

# Linux

## Ubuntu