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
    - echo "# fmisc_app" >> README.md
    - git init
    - git add README.md
    - git commit -m "first commit"
    - git branch -M master
    - git remote add origin https://github.com/stucaretech/fmisc_app.git
    - git push -u origin master
              
# *** push an existing repository from the command line. ***  
    - git remote add origin https://github.com/stucaretech/fmisc_app.git
    - git branch -M master
    - git push -u origin master

# *** remove remote origin. ***  
    - git remote remove origin
    
# *** change/update remote origin. ***  
    - git remote set-url origin git://new.url.here
    
### Plugins


### Development

Want to contribute? Great!

Make a change in your file and instantaneously see your updates!

Open your favorite Terminal and run these commands.

### Todos

 - Write MORE Commands


License
----

MIT


**Free Stuff, Hell Yeah!**





 
