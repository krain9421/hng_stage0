hng_stage0 
Slack: @Chidubem
COMMITTING FILES IN GIT

Git is a software that allows programmers to track changes in an application or project over time. In Git, committing is the process by which changes are officially added to the Git repository. 

Committing is a two step process where the specific files are first added to the staging area and then the commit command is run. The staging area is like a holding container where the files to commit are put. The reason for adding files to the staging area is that we might have a project in which we make several changes to several sets of files and we might only want to do a smaller commit on only files of a particular file type e.g .java. So we add the necessary files that have changed and then we commit those files selectively.

Below shows the simple steps involved in committing a main.java file
$ git add main.java
$ git commit -m "Your comment here"

In the second line of code, we can see that Git allows us to add comments to our commit. Comments should usually contain details like: what we are committing & why we are committing it.
It is also possible for us to add more than one file to the paging area. Simply separate the file names with spaces.
$ git add main.java settings.java
