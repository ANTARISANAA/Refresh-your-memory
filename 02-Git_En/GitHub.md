##Git 

**Definition**
 it's a version control system (vcs) for taking changes in computer files.
it help people to work on the same  project whithout having to be on the same network.

**Objectifs:**
fast
siple 
distribute

**Basic Commands:**
$git init : Initialize Git repository.
$git add <file name> : Add files to index.
$git status : See what we have in the working area.
$git commit : Commit changes .
$git push : Push the remote repository.
$git pull : Pull latest from ramote repository .
$git clone : Clone repository to a new repository.

How to start our First pproject in Github :
-Create a new folder and create a new file inside it .
-Change the view option to see .git file.
-We can add Email and user name by executing the commands :
-----$git conf --global user.name 'name.'
-----$git conf --global user.email 'email'
Then we can start to use to add our files and to use get commit to commit changes.
We can use the commands :
----$git add *.extention to add all files.extention to our repository 
(ex:$git add *.html to add all files.html )
----$git add. to add all files to our repository.


.Git ignore:
it use to tell Git which files and directories to ignore when you make a commit.

Brunches:
To create:  $git brach 'login'.
And if we wont to access to our branche  $git checkout 'login'.

NB: if we add a new file (exemple: file.html) to our brance then we switsh to master , the 'file.html' id going to be deleted , to resolve this probleme we have to merge our 'file.html' (in master) by : $git merge file .