## CONFIGURATION

| Description | Command |
| --- | --- |
| Set the user name of the commits | `git config --global user.name "username"` |
| Configure the email | `git config --global user.email *example@gmail.com` |


## BASIC USAGE

| Description | Command |
| --- | --- |
| Start git in the current path | `git init` |
| Clone an existing repository in the current path | `git clone -url-` |
| Adding all the files to the commit | `git add .` |
| Commit the files | `git commit -m "Description of the new commit"` |
| Uploading the data | `git push origin master` |


## ADDING TO THE COMMIT (staging area)

| Description | Command |
| --- | --- |
|All the directory | `git add .` |
| One file | `git add *filename` |
| All the files omitting the new files | `git add --all` |
| All the files with a specific extension | `git add *.js` |
| All the files in a dir with a specific extension | `git add *dirname*/*.js` |
| All the files in a dir | `git add *dinamer*/` |


## COMMIT

| Description | Command |
| --- | --- |
| Load the changes in the head | `git commit -m "Description of the new commit"` |
| Add and load the changes into the head | `git commit -a -m "Description of the new commit"` |
| Print an error if the commit fails | `git commit -a` |
| Adding the commit to the previous one and replacing its description, this won't be shown like a new commit | `git commit --amend -m "Description of the new commit"` |


## PUSH

| Description | Command |
| --- | --- |
| Upload the repository | `git push *originname* *branchname*` |
| Upload a tag | `git push --*tags*` |


## LOG

| Description | Command |
| --- | --- |
| Show the commits logs | `git log` |
| Show the changes in the commits | `git log --oneline --stat` |
| Show a graphic of the commits | `git log --oneline --graph` |

## DIFF

| Description | Command |
| --- | --- |
| Show the changes in a file | `git diff` |


## HEAD

| Description | Command |
| --- | --- |
| Extract a file to the head | `git reset HEAD *filename*` |
| Return the last commit and put it in the staging area | `git reset --soft HEAD^` |
| Return the las commit and this changes | `git reset --hard HEAD^` |
| Return the last 2 commits and their changes | `git reset --hard HEAD^` |


## REMOTE

| Description | Command |
| --- | --- |
| Add a remote directory | `git remote add origin *url*` |
| Change the remote directory | `git remote set-url origin *url*` |
| Removing a remote directory | `git remote rm <name/origin>` |
| List the remote directories | `git remote -v` |
| Show the remote branches | `git remote show origin` |
| Clean the remote deleted | `git remote prune origin` |


## BRANCH

| Description | Command |
| --- | --- |
| Generate a branch | `git branch *branchname` |
| List all the branches | `git branch` |
| Delete the branch and add it to the master | `git branch -d *branchname*` |
| Delete a branch without a confirm | `git branch -D *branchname*` |
| Merge 2 branchs | `git merge *branch to merge into current* -m "Description"` |
| Push a branch to server create/update | `git push -u *origin branch* *branch to send*` |


## TAG

| Description | Command |
| --- | --- |
| List the tags | `git tag` |
| Add a tag | `git tag -a *verison* - m "tagname"` |


## OTHERS

| Description | Command |
| --- | --- |
| Status of the repositorie | `git status` |
| Automatically upload | `git pull origin *branchname*` |
| Delete a file to the repositorie | `git rm *filename*` |
| Verify the changes | `git fetch` |











