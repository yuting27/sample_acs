###GitHub Tutorial

#### Installation:
* Install Git: http://git-scm.com/downloads (Windows & OS X)
* Install GitHub Desktop: https://desktop.github.com/

#### Initialization:
* Create a new empty repository
	* create through github desktop
	* create through terminal + github website
        * Create a new repository on GitHub
        * Open Terminal (for Mac and Linux users) or the command prompt (for Windows users).
* Create a repository from existing local folder
* Create a new R project in Studio with Git version control
    * https://support.rstudio.com/hc/en-us/articles/200532077-Version-Control-with-Git-and-SVN
* Clone (import) an existing Git repository

#### Work on GitHub
* Work in local repository
    * Add/Change files
    * Commit to local repository
    	* All saved changes are called commits.
	* Push to remote repository
* Work with collaboration
	* Fork and clone a (master) repository
	* Create a branch
		* Branching is the way to work on different parts of a repository at one time. It creates a snapshot of the original branch.
	* Make a commit
	* Open a pull request 
	* Merge pull request into the master branch

#### Git Glossary
* commit: record your changes to the local repository.
* push: update the remote repository with your local changes.
* pull: update your local repository to the newest commit
* clone: clone a repository into your local directory
* merge: merge another branch in to your active branch
* checkout: switch between branches


#### Work on GitHub with terminal
* Work in local repository
    * Add/Change files: `git add <filename>` or 'git add -A' if you want to add all files
    * Commit to local repository: `git commit -m "Commit message"`
	* Push to remote repository `git push`
* Work with collaboration
	* Clone a (master) repository: `git clone username@host/path/to/repository`
	* Create a branch: `git checkout -b <branchname>` 
		* Branching is the way to work on different parts of a repository at one time. It creates a snapshot of the original branch.
	* Switch back to master: `git checkout master`
	* Make a commit and push to repository: `git push origin <branchname>`
	* update local repository to newest commit: `git pull`
	* Merge another branch into you active branch: `git merge <otherbranchname>`

