# git cheat-sheet

## Markup
https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax

## Emergency commands
https://ohshitgit.com/

### How do I delete a local branch in Git?

`git branch -d <local-branch>`

### I committed and immediately realized I need to make one small change!

```
# make your change
git add . # or add individual files
git commit --amend --no-edit
# now your last commit contains that change!
```
