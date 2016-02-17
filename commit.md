# Making Changes Locally

In your working tree, you have all the latest files. You can make updates and create new files. As an example right now, open up people.md and add yourself to the table and save the file.

If you ask, Git will tell you that it noticed you made a change. Try running:

    git status

You'll probably see something like this:

    On branch master
    Your branch is up-to-date with 'origin/master'.
    Changes not staged for commit:
      (use "git add <file>..." to update what will be committed)
      (use "git checkout -- <file>..." to discard changes in working directory)
    
            modified:   users.md

We'll cover the `On branch master` part later. The `up-to-date with 'origin/master'` is talking about the three histories from before. Your local history and your view of origin's history match. `Changes not staged for commit` means the following list are modified in your working tree, but not part of the index, and not part of history.

We want to add your change to history, so the first step in creating a commit is to add your change to the index. Do this with:

    git add users.md


- `git rm`
- `git status`
- `git commit`
-- a word on commit messages and format
- `git log`
- `gitk`
- `git branch` / `git checkout -b` ?
- brief mention of `commit --amend` and `rebase` ?

Ready to [publish your work >>](publish.md)

