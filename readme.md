## GIT COMMAND LINE NOTE
### 1. BASIC COMMAND LINE

Copy project from git repository by using command line `git clone`
> `git clone https://github.com/.../your-project.git`

The git status command displays the state of the working directory and the staging area. It lets you see which changes have been staged, which haven't, and which files aren't being tracked by Git.
> `git status`

Add a change in the working directory to the staging area. 
- [x] `git add` file-name
- [x]  `git add .`
- [ ] `git add *`

A Git commit is a snapshot of the hierarchy (Git tree) and the contents of the files (Git blob) in a Git repository.
> `git commit -m "your message"`

Pushing is how you transfer commits from your local repository to a remote repo. 
> `git push`

The git pull command is used to fetch and download content from a remote repository and immediately update the local repository to match that content. 
> `git pull`

### 2. REMOTE EXISTING PROJECT TO GIT REPOSITORY
The git init command creates a new Git repository. It can be used to convert an existing, unversioned project to a Git repository or initialize a new, empty repository.
> `git init` 

The git remote add command will create a new connection record to a remote repository. 
> `git remote add origin https://github.com/.../project.git`

Add a change in the working directory to the staging area. 
> `git add .`

A Git commit is a snapshot of the hierarchy (Git tree) and the contents of the files (Git blob) in a Git repository.
> `git commit -m "your message"`

Pushing is how you transfer commits from your local repository to a remote repo. 
> `git push --set-upstream origin master`

Only first time
