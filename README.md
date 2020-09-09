
# Carpentry@Home Git Workshop
 
- git clone https://github.com/julimarchetti/2020-09-09-CCatHome-Julia.git: download the repo ffrom the web to your computer
- make sure you are not in another repo
- just like git init do only one per repo


# 2020-09-09: CarpentryCon@Home

git clone https://github.com/julimarchetti/2020-09-09-CCatHome-Julia.git: download the repo ffrom the web to your computer
make sure you are not in another repo
just like git init do only one per repo


## Branches
- 'git branch <branch_name>': create a new branch were you are ('HEAD')
- 'git switch <branch_name>': moves you to '<branch_name>'
- 'git chekcout <branch_name>': pre aug 2019 

- git branch -d <branch_name>`: this will delete <branch_name> on your local computer
- `git fetch --prune`: will update your local git tree with the remote 
- the prune will also delete references to branches that were deleted on the remote

- Each pull request is independent from one another
	- you won't know a merge conflict will happen until one of the pR merge

- 'git rebase <branch>': rebases your current branch against '<branch>', where is usually 'master' or 'gh-pages'
- make sure you are already - 
