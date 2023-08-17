## Learning Git 

### My git alias
- git unstage = "restore a file to modified from staged state, **that was not commited before**"
- git restore = "restore a file to modified from staged state, **that was commited before**
- git clean = "delete all files that was not exist before, but must be use with:"
  - -n show all files gonna be delete but do not delete it
  - -d delete all files
  - -f force to delete all files
  - -1 ask you before to delete the files
- git co = "equal to commit"
- git br = "equal to branch"
- git sw = "equal to switch"
- git db = "delete a branch"
- git sbr = "show all branches sorted by date"
- git branches = "show all branches (remote and local)"
- git l1 = "show logs on oneline"
- git last = "show last commit"
- git ch = "equal to checkout"
- git reset = ""
- git graph = "show a graph of all branch"
- git rank = "show all commits of entire users"
- git cnb = "create new branch"
- git aa = "add all files to staged from modified state and create a commit, **do not work for new files**"
- git reference = "rev-parse HEAD: get reference number of HEAD"
- git symbolic = "symbolic-ref HEAD: show branch reference of HEAD"
- git sr = "undo last commit, **only works if you have not push to a remote repo** and keep changes"
- git hr = "undo last commit, **only works if you have not push to a remote repo**"
- git cco = "change last commit, could be just the message or add more file **only works if you have not push to a remote repo**"