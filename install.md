# Installing Git
You can [experiment online](http://try.github.com) in your browser, but to do real work you're going to need to install Git, so you might as well get that out of the way now:

&nbsp;&nbsp;&nbsp;&nbsp;http://git-scm.com

(Can someone please take screenshots of each screen in the installation process and add them or email them to @babywonderland -- then remove this comment?)

The Windows installation will probably ask you a question about line-endings. Choose one of the options that says "commit Unix-style line endings", as this is how Git normally works, and is important for teams working together on multiple platforms. Normally, the default option should be just fine.


# Configuring Git
Git likely can't guess who you are, so one of the first things you need to do is tell Git a little bit about yourself. You probably only need to do this once on each computer where you install Git.

Open a terminal<sup>[1](#footnote1)</sup>, or a command prompt, and say hello to Git:

    git config --global user.email "upgoer5@example.com"
	git config --global user.name "Imak Rawkut"

This name and email address will appear and be saved as part of any commits you create.


# Signing up on GitHub
You're probably looking at this file on GitHub. PSAS is open-source, so anybody can download most of what we do by just pointing Git at our GitHub repositories. But to make changes two things must happen. First, you're going to need a GitHub account:

&nbsp;&nbsp;&nbsp;&nbsp;https://github.com/join

Then second, you'll need to be added to the PSAS (or OreSat) organization. Send Andrew an email saying who you are, your GitHub username, and that you need to be invited to the GitHub PSAS group.


Installed and configured? Let's start by [downloading a repository >>](clone.md)






<a name="footnote1"></a><sup>1</sup>  If the terminal makes your eyes glaze over, grab some caffeine and fight through it, because there really aren't any point-and-click style Git tools that make it any less confusing. To become more comfortable with using the terminal, ask the folks around you! Or check out some tutorials for linux: http://linuxcommand.org; OSX: ; or Windows:. Or search for combinations of "shell", "terminal", and "tutorial".
