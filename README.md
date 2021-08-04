# Git commands

Discarding All Local Changes
------------------------------------------------------------------------------------------------------------------------------
`$ git restore .` <br>
This change is irreversible so be sure before restoring previous local version. <br>

Deleting a Git branch
-------------------------------------------------------------------------------------------------------------------------------
Local: `$ git branch -d branch_name` or `$ git branch -D branch_name` <br>
Remote: `$ git push -d <remote_name> <branch_name>` eg: `$ git push -d origin <branch_name>`  <br>

List all remote branches
-------------------------------------------------------------------------------------------------------------------------------
`$ git branch -r` <br>

Add remote branch to local
-------------------------------------------------------------------------------------------------------------------------------
`$ git fetch <remote_name> <remote_branch>:<local_branch>` <br>
`$ git checkout <local_branch>` <br>

change remote git repository
-------------------------------------------------------------------------------------------------------------------------------
`$ git remote set-url origin <repo link>`

Set up Upstream Remote
-----------------------------------------------------------------------------------------------------------------------------
`$ git remote add upstream <repo name>`

Fetch an upstream pull request on local
-----------------------------------------------------------------------------------------------------------------------------
` $ git fetch upstream pull/<pull request no>/head:<local branch name>`

## Resources to learn
* https://www.atlassian.com/git/tutorials/learn-git-with-bitbucket-cloud
## Gir rebase
* https://git-scm.com/docs/git-rebase
