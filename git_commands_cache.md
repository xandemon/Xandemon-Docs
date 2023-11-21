# Git-Commands-Cache

Initialize any local folder as a local git repository: `git init`

Change initial branch while creating new repositories: `git config --global init.defaultBranch <branch_name>`

Connect remote repo to your local git repo: `git remote add <remote_repo_alias> <remote_repo_link>`

View all local branches: `git branch`

View all local and remote branches: `git branch -a`

Rename current branch: `git branch -M <new_branch_name>`

Delete branch: `git branch -D <branch_name>`

Create new branch from existing local branch: `git checkout -b <existing_branch_name>`

Create new branch from a remote branch: `git checkout <remote_branch_name>`

Undo last local commit by preserving changes: `git reset --soft HEAD~1`

Undo last local commit by discarding changes: `git reset --hard HEAD ~1`

Undo last n local commits: `git reset --soft HEAD~n`

Revert remote commit: `git revert <commit_hash>`

Force replace remote branch with local branch: `git push --force <remote> <branch>`

Force replace remote branch with local branch upto specified commit: `git push -f [origin] [commit_hash]:[feat/ssrReady]`
