# git and github demo

This is my first Git repository

<br>
Auther - Chandan

*******************************************************
git commond

-- git clone

-- git status

-- untracked :new files that git doesn't yet track(new file,untracked)
-- modified: changed(changes,modified)

-- staged: file is ready tobe committed
-- unmodified: unchanged

1. add modified and new file -> add(staged) -> commit(unchanged);

-- add: adds new or changed files in your working directory to the Git staging araa.
    >$git add<-file name->

--commit: it is the record of change
    >$git commit -m "some message"

--push: upload local repo content to remote repo. 
    >$git push origin main

*******************************************************************
# from local machain

Init Command

-- init: used to create a new git repo

-- git init

-- git remote add origin <- link ->

-- git remote -v: (to verify remote)

-- git branch: (to check branch)

-- git branch -M main: (to rename branch)

-- git push origin main || git push -u origin main: (to set upstream)# Learning_For_Git

********************************************************************

# Workflow

Local git

1. Create a Github repo.
    Clone >> changes >> add >> commit >> push.

********************************************************************

# Git Branch Command

-- git branch: (to check branch)

-- git branch <-new Branch name-> (to create new branch)

-- git checkout <- branch name ->:  (to navigate)

-- git checkout -b <- new branch name ->: (to create new branch)

-- git branch -d <- branch name ->: (to delete branch)


***********************************************************

# gitignore

<p>Open the file using a text editor.</p>
<p>We are just going to add two simple rules.</p>
<ul>
<li>Ignore any files with the .log extension.</li>
<li>Ignore everything in any directory named temp</li>

</ul>

<h2>Example</h2>
<p>
#ignore ALL .log files<br>
*.log

#ignore All files in ANY directory named temp<br>
temp/
</p>

<p> Now all .log file and anything in temp folders will be ignored by Git.</p>


# Rules For .gitignore

-- #text comment
