# Catatan Git Command
> **Desc :** This file is create for my git command notes. Guide for writing README code is [Here](https://guides.github.com/features/mastering-markdown/#what) or [Here](https://help.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax), for writing some table is [Here](https://help.github.com/en/github/writing-on-github/organizing-information-with-tables) and adding some badge like  ![twitter](https://img.shields.io/twitter/follow/betuahripsn?style=social)   in your README file just [click here](https://shields.io/)

## About Author
- **Name :** Betuah Anugerah
- **Email :** betuahanugerah@gmail.com
- **Github :** [My Github Libraries](https://github.com/betuah/) ![github](https://img.shields.io/github/followers/betuah?style=social) 
<hr>

| Command                               | Description                         | Example                                                |
| ------------------------------------- | ----------------------------------- | ------------------------------------------------------ |
| **git config –global user.name "[name]"** | Sets the author name respectively to be used with your commits. | git config -global user.name "betuah" |
| **git config -global user.email "[email]"** | Sets the author email address respectively to be used with your commits. | git config user.email "betuahanugerah@gmail.com" |
| **git init**   | Used to start a new repository.       | git init or git init /var/www/myproject   |
| **git clone [url]**  | Used to obtain a repository from an existing URL  | git clone https://github.com/betuah/catatan_git.git |
| **git remote add [variable name]** **[Remote Server Link]** | Used to connect your local repository to the remote server. | git remote add origin https://github.com/betuah/catatan_git.git |
| **git status** | Lists of all the files that have to be committed | git status |
| **git add [file]** | Adds a file to the staging area. | git add app.js |
| **git commit -m "[Some commit message]"** | records or snapshots the file permanently in the version history | git commit -m "Update function" |
| **git tag v1.0 [name_of_branch]** | which will create the tag to the most recent commit of the branch | git tag v1.0 master |
| **git diff** | Shows the file differences which are not yet staged. | git diff |
| **git diff -staged** | Shows the differences between the files in the staging area and the latest version present. | git diff -staged |
| **git reset [file name or path]** | This command unstages the file, but it preserves the file contents. | git reset index.html |
| **git reset [commit id]** | Undoes all the commits after the specified commit and preserves the changes locally. | git reset 052b643 |
| **git reset –hard [commit id]** | Discards all history and goes back to the specified commit. | git reset –hard 052b643 |
| **git log** | Used to list the version history for the current branch. | git log |
| **git log --oneline** | Used to list the version history for the current branch with simple view. | git log --oneline |
| **git show [commit]** | Shows the metadata and content changes of the specified commit. | git show 052b643 |
| **git branch** | Lists all the local branches in the current repository. | git branch |
| **git branch [branch name]** | Creates a new branch. | git branch v1.0 |
| **git branch -d [branch name]** | Deletes the feature branch. | git branch -d v1.0 |
| **git checkout [branch name]** | Used to switch from one branch to another. | git checkout v2.0 |
| **git checkout -b [branch name]** | Creates a new branch and also switches to it. | git checkout -b v3.0 |
| **git merge [branch name]** | Merges the specified branch’s history into the current branch. | git merge v3.0 |
| **git push [variable name]** **[branch]** | Sends the branch commits to your remote repository. | git push origin master |
| **git pull \| git pull [remote repository]** | Fetches and merges changes on the remote server to your working directory. | git pull |
| **git rm [file] --cached** | Stoping tracking any file from staging area | git rm .env --cachced |
