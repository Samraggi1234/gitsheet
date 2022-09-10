# Git Commands


* > **git init**
    * initializes/creates a new git repository
    * generally, the first command to run
---
* > **git status**
    * shows status of files
    * whether staged/modified/etc.
---
* > **git add _file_name_ / _folder_**
    * adds file/folder to the staging area
---
* > **git commit**
    * saves changes to local repository
    * creates a commit/snapshot of repository
    * > **git commit -m "_Some message about update_"**
---
* > **git log**
  * history of the repository
  * commit *some hash_id*
  * to go back to a certain commit time-
  * > **git reset _hashid_**
---
* > **git stash**
  * record the current state of the working directory and the index
  * want to go back to a clean working directory:
  * > **git stash pop**
    * bring back the undid changes
  * > **git stash clear**
    * delete everything in stash
---
* > **git remote add origin URL**
  * *remote* : not on local machine (URLs n stuffs)
  * *add* : adding a new URL
  * *origin* : (convention) name of URL
  * > **git remote -v**
    * all URLs attached to the present folder
---
* > **git branch new-branch**
  * adds a new branch
  * changes are made on a separate branch and then verified and added to main(master) branch
---
* > **HEAD**
  * A pointer which points to the current branch.
  * All new commits will be added t HEAD.
---
* > **git branch**
  * lists all branches
* > **git branch _newbranch_**
  * creates a new branch
* > **git branch --delete _branchname_**
  * deletes a branch
* > **git checkout new-branch**
  * **HEAD** points to _new-branch_
  * > **git checkout main**
    * HEAD points main
    * Branches are separated and work can be done parallely
  * > **git merge new-branch**
    * merges the new-branch with main branch
    * new-branch is a part of main branch
---
* > **git push origin master**
  * *push* : adds/pushes local files t remote repo
  * *origin* : name of URL(where to push)
  * *master* : on which branch
  * **_-f_** : forcefully
---
#### Any repository hosted on my account has origin as URL (convention)
---
* > **Fork**
  * to create a copy of a repository into own account
---
* > **git clone URL**
  * download the file/folder on a local machine
---
* **Origin : own account**
* **Upstream : from where project is forked**
---
* > **git remote add upstream project-URL**
  * adds the project URL as upstream

