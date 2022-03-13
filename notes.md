- adding a second -m in git commit adds a description to your commit (use it instead of writing a very long commit message)

After initializing a local repo and trying to connect it to a remote\*, empty repo on Github:

- git remote add origin URL is used to add the remote repo to which commits will be pushed
- after that, you use git push -u origin main to push the first time. the -u is short for upstream or
  default location to push to

\*remote also seems to refer to any other directory even on your computer, not necessarily online repositories

Q: what happens if I clone a project, checkout an early version and try to commit? What happens when I make any change actually and try to push? When does Git tell me that I can't make changes to the repo?
