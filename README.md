
![Github Profile](Screenshot.PNG)

### 1) Create a new repository on GitHub.com. To avoid errors, do not initialize the new repository with README, license, or gitignore files. You can add these files after your project has been pushed to GitHub.

### 2) Open Git Bash.

### 3)Change the current working directory to your local project.

### 4) Initialize the local directory as a Git repository.
	
	$ git init -b main
  
### 5) Add the files in your new local repository. This stages them for the first commit.
    $ git add .
    # Adds the files in the local repository and stages them for commit. To unstage a file, use 'git reset HEAD YOUR-FILE'.

### 6) Commit the files that you've staged in your local repository.
    $ git commit -m "First commit"
    # Commits the tracked changes and prepares them to be pushed to a remote repository. To remove this commit and modify the file, use 'git reset --soft HEAD~1' and commit and add the file again.


### 7) At the top of your repository on GitHub.com's Quick Setup page, click  to copy the remote repository URL.

### 8) In the Command prompt, add the URL for the remote repository where your local repository will be pushed.
    $ git remote add origin  <REMOTE_URL> 
    # Sets the new remote
    $ git remote -v
    # Verifies the new remote URL
    
### 9) Push the changes in your local repository to GitHub.com.
    $ git push origin main
    # Pushes the changes in your local repository up to the remote repository


ASSIGNMENT NO 2A GITHUB

** Commands To Execute In Visual Studio Code Terminal:
 - For Pushing First File:
  1. git --version
  2. git init
  3. git add .
  4. git status
  5. git remote add origin "link of your github repository"
  6. git commit -m "any message"
  7. If Prompted to authenticate the user, execute following commands:
   7.1 git config --global user.email "your git hub email id"
     7.2 git config --global user.name "Your git hub user name"
    8. git push -u origin master
    9. git status
    Now, check your github repository (refresh the page) whether the file is pushed or not.

 - For Pushing Second File:
  1. git add .
  2. git status
  3. git commit -m "any message"
  4. git push -u origin master
    5. git status
    Now, check your github repository (refresh the page)  whether the file is pushed or not.


    __________________________________________________________________________________________________________
   J) Install git

Windous- git bash

Ubuntu give coromand from terminal.

sudo apt-get install git

Ⅱ-Create account on bit hub

click on your repository.

click give name 03 new

commands shown local mic code are used push your your } the remote repository

①git init CInitialization command)

git add-a all the files & folders are ready, to add into the repository

git commit m "may" Cary may inside double code)

git branch -M main

git remote Connecting repository (if then there add origin local folder with remote this command gives first time is then gives umor)

git push origin main/Master first pirme

-It requires username for hups: github.com Can github afe right side at profile

photo

user name)

pod (don't give login pwd) for pwd go to settings- Developer setting - Personal access token-tokens class e click- generate new class C

[xlote give name for token eng wed pract 3

Select all option

- generate token

- copy

paste

To then add changes push changes

git add-a

git msg shown "Login page added" file danges file name

commit -m

Devops trol used for is developer's Git the is version source code mgmt. control to track wed system that allows Changes In their code tracking changes in source code, enabling multiple developers non. Linear to work tugether development.