# GITHUB WORKFLOW COMMANDS CHEATSHEET

### 0. CREATE A REPO

  Two ways, your proper repository or create an organization:
  
##### 0.1. USER PROFILE PAGE
```
  * Repositories tab
  * [New](https://github.com/new)
    * Name your repo and get the url
```
##### 0.2. CREATE AN ORGANIZATION
```
In user profile menu
    * [Your organizations](https://github.com/settings/organizations)
    * [New Organization](https://github.com/account/organizations/new)
     * Set up your team
```
### 1. UPLOAD THE MASTER FIRST COMMIT BY TERMINAL COMMANDS
    * git init
    * git add .
    * git commit -m "first commit"
    * `git remote add origin github-URL-repo`
    * git push origin master


3>  git clone projectURL                // Create a local master version without fork

4>  git checkout -b <branch-name>       // Create a new branch and switch to it

5>  git add .                           // Make some changes and then add the files and commit them:
    git commit -m "commit message"      // Then the local branch is updated

6>  git push origin <branch-name>       // Upload the local branch version to the online repo

7>  GitHub repo >>> "New Pull Request"  // Compare and edit the changes with the master and save it

8>  git checkout master                 // To update the local version go to the local master

9>  git pull origin master              // Download the new master version to the local version 

10> git checkout <branch-name>          // Come back to the pushed branch

11> git merge master                    // Update the local branch with all the master version changes

***** git reset --hard                  // to restart from the last commited version
