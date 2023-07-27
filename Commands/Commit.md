# git commit

The command `git commit` will take all tracked changes (items added with `git addd`) and package them up in what is called a commit. 

Commits come with commit messages that are required for each commit. You add a message to the commit command by using the `-m` flag follows by a message in quotes. 

A commit message _can_ be anything, but best practice dictates taht you should use that message to indicate the changes included in the commit. 

For example if we have an application we're working on where we just added the ability to register new accounts, you might add something like this: 

```
git add .
git commit -m "added register functionality"
```

Then when viewing the history of a git repository, you can pinpoint where the register functionality was added.

## Resources 
- [git commit](./Commit.md)

--- 
[Back to home](../README.md)