## GIT COMMAND LINE NOTE
### 1. Basic git commands

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

 Switches to a different branch
> `git checkout branch-name`

 Switches to a different revision of commit id.
> `git checkout commit-id`

Create and move directly new branch
> `git branch -b your_branch_name`

To check we are on the good branch
> `git branch -`

Merge your branch into main branch
> `git merge branch-name -m "your_message"`
### 2. Remote existing project to github repository

- [x] `git init` 
- [x] `git remote add origin https://github.com/.../project.git`
- [x] `git add .`
- [x] `git commit -m "your message"` 
- [x] `git push --set-upstream origin master`

### 3. Git global Configuring
- [x] `git config --global user.name "rady y"`
- [x] `git config --global user.email "rady@gmail.com"`

>Note: You can check your global configuration in your Windows environment:`C:\Users\YOUR_USER\.gitcofig`

### 4. Github credentials
When you start to use new GitHub account please modify your credentials if you have problem on push project.

<img src="https://i.stack.imgur.com/NejcV.png">