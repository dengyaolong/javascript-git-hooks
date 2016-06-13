# javascript-git-hooks
Some useful git hooks for javascript repo.

# how to use
ln/copy the hooks file to you repo/.git/hooks/

```
ln -s pre-commit /your/repo/.git/hooks/precommit
```

# pre-commit
If the repo exists the "console.log", the pre-commit hook will give you a warning and the detail info.
