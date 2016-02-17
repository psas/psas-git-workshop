# Copying / Downloading a Repository
To copy a repository to your computer, use `git clone`. This is a one-time operation (once per repository) that copies all the files and history from somewhere else -- GitHub, in this case -- to your computer, and it will automatically give you the latest copy of all the files. Git remembers the "somewhere else" you copied from, and has a name for that place: *origin*.

Let's start by copying this repository:

    git clone https://github.com/psas/psas-git-workshop

You'll probably see something like this:

    Cloning into 'psas-git-workshop'...
    remote: Counting objects: 9, done.
    remote: Total 9 (delta 0), reused 0 (delta 0), pack-reused 9
    Unpacking objects: 100% (9/9), done.
    Checking connectivity... done.

That means it worked. You have your own local copy now. You can look around a bit...

    > cd psas-git-workshop
	> ls
	README.md        clone.md         glossary.md      install.md
...etc...

All the history has been copied, too. We'll look at that, next, as we [explore Git concepts >>](concepts.md)




If you wanted to start a completely new repository instead of copying an existing one, you'd use `git init` intsead of `git clone`, like this:

    git init my-project-name

Git would dutifully say it had initialized an empty repository, and you could `cd my-project-name` and begin creating or adding files, which we'll cover later.

