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

### 1. UPLOAD THE MASTER FIRST COMMIT WITH TERMINAL COMMANDS
  * git init
  * git add .
  * git commit -m "first commit"
  * `git remote add origin **github-URL-repo**`
  * git push origin master

  To create a local version
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
