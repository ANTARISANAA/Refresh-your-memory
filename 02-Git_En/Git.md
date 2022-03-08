## Git 

### **Definition**
    It's a version control system (vcs) for taking changes in computer files.
    It help people to work on the same  project whithout having to be on the same network.

### **Objectifs:**
+ Fast
+ Simple 
+ Distribute

### **Basic Commands:**
#### **Initialize Git repository:**
    $git init 
#### **Add files to index:**/
     $git add <file name>
 #### **See what we have in the working area:**
     $git status
 #### **Commit changes :**
     $git commit
 #### **Push to remote repository:**
    $git push
 #### **Pull latest from ramote repository :**
    $git pull
 ####  **Clone repository to a new repository:**
    $git clone

### **How to start our First project in Github :**
+ Create a new folder and create a new file inside it .
+ Change the view option to see .git file.
#### We can add Email and user name by executing the commands :
    $git conf --global user.name 'name.'
    $git conf --global user.email 'email'
 Then we can start  to add our files and to use get commit
 to commit changes.
+ We can use the commands :
  + **$git add *.extention** to add all files.extention to our  repository 
    (ex:$git add *.html to add all files.html )
  + **$git add.** to add all files to our repository.


### **.Git ignore file :**
 It use to tell Git which files and directories to ignore when you make a commit.

### **Branches:**
 #### To create a branch: 
     $git branch 'login'.
 #### And if we wont to access to our branch
    $git checkout 'login'.

## NB:
       If we add a new file (exemple: file.html) to our brance then we switsh to master , the 'file.html' id going to be deleted, 
       to resolve this probleme we have to merge our 'file.html' (in master) by :$git merge file.

# To be continued...
