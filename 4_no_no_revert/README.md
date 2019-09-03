# Git Lab
---

> Note: You will want to open this README in the original repository you copied it from, 
> as the revert will revert it back to the previous version

This is a single page website that explains git and some basic examples.

So maybe the gif doesn't fit the mood of our site. Let's revert the change.

A `revert` is a special form of `commit` that puts a repository back the way it was before a given `commit`. If you haven't noticed by now, git commits are referenced by a hash that is unique to the commit. In addition to a hash, the last `commit` to a repo is also referenced via `HEAD`. So to revert the last commit, we simply issue:

```
➜  lab git:(master) git revert HEAD --no-edit
[master f129260] Revert "Revert "Revert "added changes"""
 Date: Tue Sep 3 14:38:58 2019 -0500
 2 files changed, 15 insertions(+), 13 deletions(-)
 rewrite README.md (75%)
➜  lab git:(master) git status
On branch master
nothing to commit, working tree clean
➜  lab git:(master)
```

Note that the `--no-edit` flag simply aborts opening the editor to change the message that goes with this revert.

It should be noted that a revert *does not* delete history in your repository. Rather, it recommits the commit 
before the commit you specify to revert. If you need to completely re-write history (you probably don't), use 
`git rebase` (not covered here). Please do not use `git rebase` without reading several how-tos first, as they 
can completely destroy previous work in an un-revertable fasion.

When you are finished with this step, copy the folder `5_branch_creation` and continue from there.