# Git Lab
---

This is a single page website that explains git and some basic examples.

We shouldn't push to master. We should, ideally, push to a branch that isn't master, then make sure 
the code is ok before moving the code into master. Usually this also involves other team members
reviewing your code and offering suggestions.

To branch, we use the `git branch -b <branch name>` command, then `checkout` the branch so that all 
our changes are tracked in it instead of master. You can do that like this:

```
➜  lab git:(master) git branch feature_branch
➜  lab git:(master) git checkout feature_branch
Switched to branch 'feature_branch'
➜  lab git:(feature_branch)
```

You can now commit the changes in this branch, just like you would in `master`. Remember that instead of running `git push origin master`, you'll need to run `git push origin feature_branch` When you're done, move to the next folder!