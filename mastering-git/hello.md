## hello world

## git add ./ (to add all file, get ready into git)

## git commit -m 'some comment' (commit the file into git)

## git log (check git history)

## git checkout .... example: 8fb5fb88cf733ddd48cf9f5cb87e9ac704535ebe(it command the head where it locate, which mean which branch we are using)

## git branch (check the branch of the git, mostly it is master or main) so if we want to change our branch master -> main

## git branch -m master main (change the master branch to main)

## git branch -m main

## git remote add origin https://github.com/Sinta-chaing/mastering-git.git

## (remote the local reposite to the remote reposite on git)

## noted that we can have multiple remote repositive by change the "origin"

## git push -u origin main ( push the ready file to the remote repositive github), origin refer to https://github.com/Sinta-chaing/mastering-git.git which mean now

## origin = https://github.com/Sinta-chaing/mastering-git.git

## git branch branch-name (create the new branch beside the main)

## pro tip: git checkout -b feature-branch (create a new branch name and alocate head on it) create + checkout

## noted that the new branch will create base on the current branch.

## so if we want to create a multiple branch on the main branch please move to main branch before create the new branch, otherwise it will create on the branch that it now main branch

# git branch new-branch-name source-branch(this is how we create a new branch inherite from the specific branch we want to without checkout that branch)

## git push --set-upstream origin feature-branch (publish the new branch into remote repositive on github)

## git push -u origin feature-branch (tracking relationship between local branch and remote branch) so when every we want to push something using it just write

## git push
