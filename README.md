# Git? What?
[Git](https://git-scm.com) is a program to do version control. You've probably saved multiple versions of a file before: "thesis draft", "thesis", "thesis final", "thesis final 2", etc. Maybe you were even organized enough to name them "thesis version 1", "thesis version 2", and so on. Version control, like Git, is a way to organize, document, and share this progression for a collection of files.


You can think of this progression like a timeline:

![document timeline](https://github.com/psas/psas-git-workshop/blob/master/images/doctimeline.png)

Each set of changes is marked by a tick on the timeline -- a version. You can think of it as a saved snapshot of your file(s) at that moment. These snapshots are created by performing a "commit" action, and so the snapshots themselves have come to be known as "commits".


And usually, the timeline is turned sideways so the old stuff is at the bottom, and the new stuff at the top.

![vertical timeline](https://github.com/psas/psas-git-workshop/blob/master/images/doctimeline_vert.png)

A lot of explanations of Git and documentation about Git describe actions with pictures like this. And there's a tool -- called gitk -- to visualize all your commits this way.

![repository timeline](https://github.com/psas/psas-git-workshop/blob/master/images/repotimeline.png)


Git is unintuitive, but it can help to remember this timeline analogy. All of the commands you'll use in Git deal with creating and manipulating this timeline, sharing (sending or receiving) timelines between collaborators, and combining work done on indivdual timelines into a single, merged timeline.

Ready to get started? [next >>](install.md)

