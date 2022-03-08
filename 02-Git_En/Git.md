## Git 

### **What is Git ?**
    It's a version control system (vcs) for taking changes in computer files.
    It lets you and others work together on projects in a locale repository and we publish to others from anywhere.

### **Objectifs:**
+ To be Fast
+ To be Simple 
+ To be Distribute
### **Definitions**
+ **Repository :**
    This is the place where Git will store all its objects: versions, branches, tags...
+ **Working copy :**
    Contains the current modifications (this is the current directory).
+ **Staging area (or index) :**
    List of modifications made in the working copy that we want to include in the next commit.
+ **Commit :**
    consistent set of changes.
### **Commit functionality :**
   + Compile.
   + Function.
   + Mean.
### **Basic Commands:**
#### **Initialize Git repository:**
    $git init 
#### **Add files to index:**
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
 #### **To add all files.extention to our  repository:**
    $git add *.extention
    (ex:$git add *.html to add all files.html )
 #### **To add all files to our repository:**
    $git add.
 ### **First steps**
 #### Configure user name :
    $git Config --global user.name "my name" 
#### configure user email : 
    $git Config --global user.email "my email"

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
