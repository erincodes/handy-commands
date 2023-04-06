# Git

- Version control
- Buttons available in VSCode panel, but sometimes you have to go command line (or prefer to!)

## `git merge --abort`

- Backs you out of a `git merge`, no harm no foul
- Helpful if you want to see if there are conflicts, but then want to cancel the merge

## `git stash`

- Saves your active changes but removes them from your current diff

## `git stash pop`

- Drops in your previously stashed changes
- 🔑 Pro tip: you can pop changes between branches!
  x

## `git cherry-pick [commitHash]`

- Merges the only changes from a specific commit hash into your working branch
- Handy for collaboration
- Helpful documentation: https://www.atlassian.com/git/tutorials/cherry-pick
