
# **Git**

### **Definition**

```
    It's a version control system (vcs) for taking changes in computer files.
    Whithout having to be on the same network, a team can work and share projects using this amazing .
    Great, it realy helpfull, so , in this part of our summarize , we're going to discover how to get start with this magic world. 
```

### **Objectifs:**

+ Fast
+ Simple
+ Distribute

### **Branches in Git :**

Git branches are effectively a pointer to a snapshot of your changes.When you want to add a new feature or fix a bug—no matter how big or how small—you spawn a new branch to encapsulate your changes.This makes it harder for unstable code to get merged into the main code base, and it gives you the chance to clean up your future's history before merging it into the main branch.

In our repository we should have a **master or main** and **develop** branches to impliment our git-flow .
The default branch name in Git is **master** . As you start making commits, you're given a master branch that points to the last commit you made.Every time you commit, the **master branch** pointer moves forward automatically.

![Resume](/Images/master_branchs.PNG)

The git branch command lets you create, list, rename, and delete branches. It doesn’t let you switch between branches or put a forked history back together again. For this reason, git branch is tightly integrated with the git checkout and git merge commands.

### **Common Option**

List all of the branches in your repository.

```
$git branch
$git branch --list
```

Create a new branch called ＜branch＞

```
$git branch <branch>
```

Delete the specified branch

```
$git branch -d <branch>
```

Force delete the specified branch

```
$git branch -D <branch>
```

Rename the current branch to ＜branch＞

```
$git branch -m <branch>
```

List all remote branches

```
$git branch -a
```

### **Creat branch (develop)**

```
$git checkout -b develop
```

### **to switch to this branch**

```
$git checkout develop
```

#### **Merge the feature branch**

```
$git merge <file>
```

## NB

```
If we add a new file (exemple: file.html) to our brance then we switsh to master , the 'file.html' id going to be deleted, 
to resolve this probleme we have to merge our 'file.html' (in master) by :$git merge file.
```

### **Basic Commands:**

+ **$git init :** Initialize Git repository.
+ **$git add <file name>** : Add files to index.
+ **$git status :** See what we have in the working area.
+ **$git commit :** Commit changes .
+ **$git push :** Push the remote repository.
+ **$git pull :** Pull latest from ramote repository .
+ **$git clone :** Clone repository to a new repository.

### **How to start our First pproject in Github :**

+ Create a new folder and create a new file inside it .
+ Change the view option to see .git file.
+ We can add Email and user name by executing the commands :

```
 $git conf --global user.name 'name.'
 $git conf --global user.email 'email'
 ```

 Then we can start  to add our files and to use get commit
 to commit changes.

+ We can use the commands :

```
$git add *.extention
```

To add all files.extention to our  repository.

```
(ex:$git add*.html to add all files.html )
```

```
 $git add.
 ```

To add all files to our repository.

### **.Git ignore:**

 ```
 It use to tell Git which files and directories to ignore when you make a commit.
```

# **Git Merge**

Merging is Git's way of putting a forked history back together again. The git merge command lets you take the independent lines of development created by git branch and integrate them into a single branch.

## **How it works**

Git merge will combine multiple sequences of commits into one unified history. In the most frequent use cases, git merge is used to combine two branches.

For exemple we have this branch that is based off the main branch and we wont to merge it to our main  (master) branch.

Before merge :

![Resume](/Images/before-merge.PNG)

After merge :

![Resume](/Images/after-merge.PNG)

### **Steps before merge**

+ Confirm the receiving branch.
(by executing *git satus* Execute git status to ensure that HEAD is pointing to the correct merge-receiving branch. If needed, execute git checkout to switch to the receiving branch. In our case we will execute git checkout main.)

+ Fetch latest remote commits.
+ Then we can merge Merging.

# **Git flow**

it's one of the most popular Git branching strategies, in the git flow we can find five different branch types :

### **Main (Master)**

The main branch is created as the start of our project and is maintained throughout the development process.

### **Develop Branch**

Contains pre-production code with newly developed features that are in the process of being tested.

### **Supporting Branches**

When developing with Git flow, there are three types of supporting branches with different intended purposes: feature, release, and hotfix.

### **Feature Branch**

It is used when adding new features to your code.
When working on a new feature, you will start a feature branch off the develop branch, and then merge your changes back into the develop branch when the feature is completed and properly reviewed.

### **Release Branch**

The release branch should be used when preparing new production releases. Typically, the work being performed on release branches concerns finishing touches and minor bugs specific to releasing new code, with code that should be addressed separately from the main develop branch.

### **Hotfix Branch**

The hotfix branch is used to quickly address necessary changes in your main branch.

## **The Git Flow Diagram**

![Resume](/Images/GitFlow.PNG)
