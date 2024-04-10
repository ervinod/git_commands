# Git Commands

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

Here is list and syntax of some important git commands that every developer must konw to use git version control effectively

  - Syntax
  - Example


# *** get checkout from git repository *** 
    - git add .
    - git commit -m "your comment"
    - switch to branch(if required)
    - git checkout branch_name

# *** create and switch to new branch: *** 
    - git checkout -b new_branch_name
    - git add .
    - git commit -m "your comment"
    - git push origin branc_name

# *** to push code *** 
    - git add .
    - git commit -m "your comment"
    - git push origin branc_name


# *** pull code (to get latest code) ***
    - git add .
    - git commit -m "your comment"
    - git pull origin master

# *** init new repo ***
    - cd existing_folder_name
    - git init
    - git remote add origin "url that end with .git"
    - git add .
    - git commit -m "Initial commit"
    - git push -u origin master
    
# *** create a new repository on the command line. ***    
    - git init
    - git remote add origin https://github.com/my_company/my_app.git
    - git add README.md
    - git commit -m "first commit"
    - git branch -M master
    - git push -u origin master
              
# *** push an existing repository from the command line. ***  
    - git remote add origin https://github.com/my_company/my_app.git
    - git branch -M master
    - git push -u origin master

# *** remove remote origin. ***  
    - git remote remove origin
    
# *** change/update remote origin. ***  
    - git remote set-url origin git://new.url.here
    
# *** reomve local commit from history. ***  
    - git reset --soft HEAD^1
    
    
 # *** delete local and remote branch ***  
 
    -Rename the local branch to the new name
        -If you are on the branch you want to rename:
         git branch -m new-name

        -If you are on a different branch:
         git branch -m old-name new-name
     
    -Delete the old branch on remote - where <remote> is, for example, origin
      git push <remote> --delete <old_name>

    -Or shorter way to delete remote branch [:]
      git push <remote> :<old_name>

    -Prevent git from using the old name when pushing in the next step.
     Otherwise, git will use the old upstream name instead of <new_name>.
      git branch --unset-upstream <new_name>

    -Push the new branch to remote
      git push <remote> <new_name>

    -Reset the upstream branch for the new_name local branch
      git push <remote> -u <new_name>
      
    -other way - https://stackoverflow.com/a/45561865
 
 # *** add tag to commit. ***  
    - git git add .
    - git commit -m "some description"
    - git tag tag_name ///ex. git tag app_release_android_qa_0.0.7_1 
    - git push origin master # push the commit
    - git push --tags origin # push the tags
    
 
 # *** delete local tag. ***
    - git tag -d app_release_android_0.0.7_1

# *** delete remote tag. ***
    - git push --delete origin app_release_android_0.0.7_1

# *** user repo without password. ***
    - url = https://myusername:kaeXedbWfhWxxxxxxx@bitbucket.org/my_company/my_project.git
    set git remote in above way either in config file or from commandline
    

### Plugins

### Development

Want to contribute? Great!

Make a change in your file and create pull request to see your updates!

Open your favorite Terminal and run these commands.

### Todos

 - Write MORE Commands


License
----

MIT


**Free Stuff, Hell Yeah!**





 
