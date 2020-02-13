# ICS Rate

## Contribution guidelines
  1.  Clone the repo to your local machine
  2.  Create a new branch 
      `git checkout -b feature_branch_name`
  3.  Push the local branch to the remote
      `git push -u origin feature_branch_name`
  4.  Do your work on the branch
  5.  Commit and push your changes, make sure to include a description of what your changes are
  6.  Create a pull request to merge changes to master
  
  Don't make changes directly to master!! (changes to the readme are ok)
  
## Writing/testing code locally
  1.  Make sure you are in the `ics-rate` directory
  2.  **Before writing code, make sure to run `git pull origin master` to make sure you are up to date with master**
  3.  Changes are made in the `src` folder
  4.  To host your changes locally, run `npm run start`
  5.  When you are sure there are no errors in your code, push to remote and create a pull request
  
## Deploying to Github Pages
  1. Switch branch to master `git checkout master` (do not deploy from any other branch, make sure your changes get merged to master before you deploy)
  2. Run `npm run deploy`
  3. Within a few min the [site](https://icsrate.github.io/webpage/) should be updated
