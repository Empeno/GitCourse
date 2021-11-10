# Git Course in VS Code

## Important
VS Code and other IDEs will leverage your machine's Git installation, so you need to install Git first before you get these features. Make sure you install at least version 2.0.0.
* 	[Installing Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)


## Popular Ressources
* 	[Git Documentation](https://git-scm.com/doc)
* 	[Git Book](https://git-scm.com/book/en/v2)
* 	[Git Videos](https://git-scm.com/videos)
* 	[Git Cheat sheet](https://github.github.com/training-kit/downloads/github-git-cheat-sheet.pdf)


## Source Control Activity Bar
The Source Control icon in the Activity Bar on the left will always indicate an overview of how many changes you currently have in your repository. Selecting the icon will show you the details of your current repository changes: CHANGES, STAGED CHANGES and MERGE CHANGES.

Clicking each item will show you in detail the textual changes within each file. Note that for unstaged changes, the editor on the right still lets you edit the file: feel free to use it!

You can also find indicators of the status of your repository in the bottom-left corner of VS Code: the current branch, dirty indicators, and the number of incoming and outgoing commits of the current branch. You can checkout any branch in your repository by clicking that status indicator and selecting the Git reference from the list.

###
**Tip:** You can open VS Code in a sub-directory of a Git repository. VS Code's Git services will still work as usual, showing all changes within the repository, but file changes outside of the scoped directory are shaded with a tool tip indicating they are located outside the current workspace.
