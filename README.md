# Git is a product invented by Linux Torwarld, same per who found Linux

# Git

git is a product from Linus Torwarlds, the same person who is a major contributor and founder of LINUX


### Important Notes and commands related to GIT 

### git : Is a local version control system 
### github, bitbucket, gitlab are the Central Version Systems 

#### What is GIT ?

```
Git is a version control system used by almost all the organizations to version control their development and parallel development using branches.
```

#### What is a branch in GIT ?
```
A branch is a copy of the code which allows the developers to test without touching the main code and this helps multiple developers to contribute parallely.

By default, main is the branch which should be the source of truth or production ready code.
```
 
 #### How can you control parallel development and how multiple developers can contribute and develop the code parallely ?

 ```
 A branch is a version of your repository, or in other words, an independent line of development. A repository can contain multiple branches, which means there are multiple versions of the repository.

Among all, main / master branch is something which you should always a checkout to create a new /feature branch
```



### Git Branch Naming Strategy 

```
Branching Naming Strategy will be based on the organizational standards.  

And based on what you're working on, name should define that.

Typically, either you work on  :
    a)  feature       [ feature/payment-enhancement ,  feature/password-auth ]
    b)  hotfix        [ hotfix/defect-correction ]
    c)  bug           [ bug/payments-correction ]
```
# Change request can be normal, emergency etc

Hotfixes are used to addess quick correction of a bug or a defect usually to expedit the process and place corrections on prod straight away.


### Common Git Commands

```
    $ git branch                                            // shows you which branch you're on right now 
    $ git branch branchName                                 // Creates a branch with a name brancName by taking your branch code as a source 
    $ git checkout branchName                               // Switches your branch to branchName 
    $ git checkout -b branchName                            // Creates branch and switches to the branch
    $ git pull origin branchName                            // origin represents remote repository
    $ git push origin branchName                            // pushes changes to remote repository
    $ git fetch origin branchName                           // Downloads the changes, but they won't be applied, they will stay in staging
    $ git merge                                             // Downloaded changes will be applied


```

### Git Fetch vs Git Pull 

```
The key difference between git fetch and pull is that git pull copies changes from a remote repository directly into your working directory, while git fetch does not. The git fetch command only copies changes into your local Git repo and if you want to merge your changes fetched by git fetch, switch to the branch of your choice and then do a git merge. The git pull command does both
```


### PS :

```
Whenever you push any changes and if they look good and stable on main branch, then you will raise/create a create a Git Tag.

Git Tag : Creating a name to a commit, which can referenced later and using that we can make the software.

Git and Linux are like oceans, infinite things are there to learn. Both of them are created by the same person : Linux Torvolds.
```


#### GIT Has Branch Protection Rules Enabled to ensure you cannot push your changes directly to the MAIN Branch and always changes has to go through Pull Request only.

### Command to give a name in your commit history 

```
        git config --global user.name "CodingManoj"
        git config --global user.email "CodingManoj@gmail.com"
```


### command to give a name in your commit history
---

git config --global user.name "hidyathms"
git config --global user.email "hidayathms@outlook.com"

---
