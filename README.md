# ConsoleApp1
<h1>
  <b>  Creating a repo from existing project file </b>
</h1>
# Creating a repo from existing project file

# …or create a new repository on the command line
- <b>create a file for readme</b>: echo "# ConsoleApp1" >> README.md
- <b>initialize git</b> : git init
- <b>add readme</b>     : git add README.md
- <b>commit </b>        : git commit -m "first commit"
- <b>repo url</b>       : git remote add origin https://github.com/aykutmayali/ConsoleApp1.git
- <b>send to repo</b>   : git push -u origin master
                
#  …or push an existing repository from the command line
- git remote add origin https://github.com/aykutmayali/ConsoleApp1.git
- git push -u origin master

#  …or import code from another repository
- You can initialize this repository with code from a Subversion, Mercurial, or TFS project.

-  <b>sync</b>      : git pull
-  <b>upload all</b>: git add .
-  <b>commit all</b>: git commit -m "second commit"
-  <b>send all</b>  : git push -u origin master
        
        
