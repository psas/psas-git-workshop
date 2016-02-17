# Understanding How Git Works
The one-time setup stuff is done and you're ready to begin making additions and changes now. But first you need to understand some concepts.

## Working Tree, Index, History
There are three "areas" on your local computer that matter to Git:
* working tree: The files you're looking at or working on right now. When you cloned the repo a moment ago, Git automatically created the latest version of all the directories and files in this repository for you. Those are collectively called the working tree. Computer scientists are an ecologically-minded bunch, so they like to call anything that's narrow at one end and wide an the other a "tree."

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![tree](https://github.com/psas/psas-git-workshop/blob/master/images/tree.png)

* history: This is your local timeline, the series of snapshots that you have copied from others and/or created yourself.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![history](https://github.com/psas/psas-git-workshop/blob/master/images/history.png)

* index: In-between the working tree and history is a staging area called the index. It's sort of like an assembly workbench. Changes are chosen from the working tree then combined together in this staging area. The index holds which changes from the working tree will become part of the next commit.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![index](https://github.com/psas/psas-git-workshop/blob/master/images/index.png)

Why is there an index? Why aren't all changes automatically committed? It turns out that the index is a useful feature and sometimes you don't want all changes committed automatically. You'll just have to trust me on this one.

## Sharing
One of the things Git is supposed to do for us is let us collaborate and share our work with others, right? When you share your work with Git, what gets shared is the history. Git does not share your index, nor your working tree. That makes things easier, but Git still has to keep track of two histories for you: [origin](https://github.com/psas/psas-git-workshop/glossary.md#origin)'s history, and your local history. Initially, they're the same.

![history after clone](https://github.com/psas/psas-git-workshop/blob/master/images/history1.png)

We'll get to how later, but when you make changes and add commits, that updates your local history. It doesn't change anything about origin yet. But Git knows your history is one commit ahead of origin.

![history after local commit](https://github.com/psas/psas-git-workshop/blob/master/images/history2.png)

But we've only talked about your local computer so far. Changes from others might get published to GitHub. So the picture really looks like this:

![three sets of history](https://github.com/psas/psas-git-workshop/blob/master/images/history3.png)

There are actually *three* versions of history: GitHub's history, your local history, and your local view of GitHub's history.

Okay, enough concepts! Can we get to [making changes >>](commit.md) already?

