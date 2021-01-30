# GITHUB WORKFLOW COMMANDS CHEATSHEET

### 0. CREATE A REPO

  Two ways, your proper repository or create an organization:
  
##### 0.1. USER PROFILE PAGE
  * Repositories tab
  * [New](https://github.com/new)
    * Name your repo and get the url
    
##### 0.2. CREATE AN ORGANIZATION
In user profile menu
  * [Your organizations](https://github.com/settings/organizations)
  * [New Organization](https://github.com/account/organizations/new)
   * Set up your team

Then in the local code
### 1. UPLOAD THE MASTER FIRST COMMIT WITH TERMINAL COMMANDS

|git init|Initialize git files|
|------|------|
|git add .| Storage the current changes|
|git commit -m "first commit"| Create a point of changes with description message|
|`git remote add origin github-URL-repo`| Link the local git files with the online repository |
|git push origin master| Upload to the master|
|------|------|
  
With all this step you're creating the base code to start to working on.
Ideally the *master* version it is a part of the code that you never modify
unless you are sure of the changes you're makinge.
To have a 'testing version' you need to create a *branch*
Basically, a copy of you *master* where you do changes without affect the main code

  To work in a local version
  * git clone projectURL                // Create a local master version without fork
  * git checkout -b <branch-name>       // Create a new branch and switch to it
  * git add .                           // Make some changes and then add the files and commit them:
  * git commit -m "commit message"      // Then the local branch is updated
  * git push origin <branch-name>       // Upload the local branch version to the online repo
  * GitHub repo >>> "New Pull Request"  // Compare and edit the changes with the master and save it
  * git checkout master                 // To update the local version go to the local master
  * git pull origin master              // Download the new master version to the local version 
  * git checkout <branch-name>          // Come back to the pushed branch
  * git merge master                    // Update the local branch with all the master version changes

***** git reset --hard                  // to restart from the last commited version
