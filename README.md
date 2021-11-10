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

## Three Git states
Git has three main states that your files can reside in: modified, staged, and committed:

* Modified means that you have changed the file but have not committed it to your database yet.
* Staged means that you have marked a modified file in its current version to go into your next commit snapshot.
* Committed means that the data is safely stored in your local database.

This leads us to the three main sections of a Git project: the working tree, the staging area, and the Git directory.
![Git working tree](https://git-scm.com/book/en/v2/images/areas.png "Git working tree")

## Commit
Staging (git add) and unstaging (git reset) can be done via contextual actions in the files or by drag-and-drop.

![stage changes in VS Code](https://code.visualstudio.com/assets/docs/editor/versioncontrol/stage-changes.png "Stage changes")

You can type a commit message above the changes and press Ctrl+Enter (macOS: ⌘+Enter) to commit them. If there are any staged changes, only those changes will be committed. Otherwise, you'll get a prompt asking you to select what changes you'd like to commit and get the option to change your commit settings.

We've found this to be a great workflow. For example, in the earlier screenshot, only the staged changes to overview.png will be included in the commit. Later staging and commit actions could include the changes to versioncontrol.md and the two other .png images as a separate commit.

More specific Commit actions can be found in the Views and More Actions ... menu on the top of the Source Control view.
![Views and More actions](https://code.visualstudio.com/assets/docs/editor/versioncontrol/scm-more-actions.png "Views and More actions")