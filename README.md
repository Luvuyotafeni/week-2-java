# week-2-java
Git Version Control
Git Version Control is a software that tracks changes to a file or set of files over time so that you can recall specific versions later. It also allows you to work together with other programmers or developers. The version control system is a collection of software tools that help a team to manage changes in a source code. It uses a special kind of database to keep track of every modification to the code.

What is Git?
Git is a distributed version control system (DVCS) that is widely used in software development to manage and track changes in source code. It was created by Linus Torvalds in 2005 to help manage the development of the Linux kernel. Git is designed to be fast, flexible, and efficient, and it has become the de facto standard for version control in the software development industry.

Version Control:
Git allows developers to track changes in their code over time. It maintains a history of modifications, making it possible to revert to previous states, compare changes, and collaborate with others.

Distributed:
Unlike centralized version control systems, Git is distributed. Each developer has a complete copy of the repository, including its entire history. This allows for offline work and makes collaboration more flexible.

Branching and Merging:
One of Git's most powerful features is its support for branching and merging. Developers can create branches to work on new features or bug fixes independently of the main codebase. Once a branch is ready, it can be merged back into the main branch.

Committing:
Git uses commits to record changes to the repository. Each commit has a unique identifier (SHA-1 hash) and includes information about the changes made, the author, and a timestamp.

Remote Repositories:
Git supports remote repositories, which can be hosted on platforms like GitHub, GitLab, or Bitbucket. This allows multiple developers to collaborate on a project, share changes, and contribute to a shared codebase.

GitHub and GitLab:
GitHub and GitLab are web-based platforms that host Git repositories. They provide additional features such as issue tracking, pull requests, and collaboration tools. Developers often use these platforms to share and contribute to open-source projects.

Command-Line Interface (CLI) and GUI Tools:
Git can be used through a command-line interface (CLI), which is the traditional and powerful way to interact with Git. Additionally, there are various graphical user interface (GUI) tools available to make Git more accessible for those who prefer a visual interface.

Open Source:
Git is open source and free to use. Its popularity and flexibility have led to widespread adoption in the software development community.

Distributed Version Control:
Git is a distributed version control system, meaning that each developer has a complete copy of the repository, including its full history. This decentralization allows for flexibility, offline work, and efficient collaboration among developers.

Branching and Merging:
Git provides robust support for branching and merging. Developers can easily create branches to work on specific features or fixes without affecting the main codebase. Merging branches is a straightforward process, allowing for the integration of changes from multiple sources.

Speed and Performance:
Git is known for its speed and efficiency. Many operations in Git, such as committing, branching, and merging, are performed locally without the need for a network connection. This results in a fast and responsive version control system, even for large projects.

Data Integrity:
Git uses a cryptographically secure hash function (SHA-1) to generate unique identifiers for each commit. This ensures the integrity of the version history. If any part of the repository is corrupted, Git can detect and handle it, maintaining the reliability of the versioned data.

Staging Area (Index):
Git introduces a staging area, also known as the index, where changes can be selectively prepared before committing. This allows developers to control which modifications are included in a commit, providing granularity and precision in version control.

Compatibility and Interoperability:
Git is platform-agnostic and works seamlessly across various operating systems (Windows, macOS, Linux). Additionally, it can interact with and integrate changes from other version control systems, making it versatile and compatible with diverse development environments.

Easy to Learn and Use:
Git's command-line interface (CLI) is straightforward and well-designed, making it relatively easy for developers to learn and use. Additionally, there are numerous graphical user interface (GUI) tools available for those who prefer a visual approach.

Community and Ecosystem:
Git has a large and active community of developers. This community support, coupled with extensive documentation, forums, and tutorials, makes it easy for users to find help and resources. The ecosystem around Git includes a variety of third-party tools, plugins, and integrations.

GitHub and GitLab Integration:
Platforms like GitHub and GitLab provide hosting services for Git repositories and offer additional features such as issue tracking, pull requests, and collaboration tools. The integration of Git with these platforms enhances project management, code review, and team collaboration.

Benefits of using Git
This helps us keep track of all the changes that we have done on our projects, this helps save time, it supports offline working, ability to undo mistakes

Git Tools
Git tools
To explore the robust functionality of Git, we should learn about git tools. Git comes with some tools like Git Bash, Git GUI to provide the interface between machine and user. It supports inbuilt as well as third-party tools.
Git comes with built-in GUI tools like git bash, git-gui, and gitk for committing and browsing. It also supports several third-party tools for users looking for platform-specific experience.

Git Package Tools
Git provides powerful functionality tools such as commands, command line, Git GUI. 

GitBash
Git Bash is an application for the Windows environment. It is used as Git command line for windows. Git Bash provides an emulation layer for a Git command-line experience. Bash is an abbreviation of Bourne Again Shell. Git package installer contains Bash, bash utilities, and Git on a Windows operating system.

Git Bash Commands
Git Bash comes with some additional commands that are stored in the /usr/bin directory of the Git Bash emulation. Git Bash can provide a robust shell experience on Windows.

Git Bash Commands
Git Bash comes with some additional commands that are stored in the /usr/bin directory of the Git Bash emulation. Git Bash can provide a robust shell experience on Windows.

Git GUI
Git GUI is a powerful alternative to Git BASH. It offers a graphical version of the Git command line function, as well as comprehensive visual diff tools. We can access it by simply right click on a folder or location in windows explorer.

Gitk
gitk is a graphical history viewer tool. It's a robust GUI shell over git log and git grep. This tool is used to find something that happened in the past or visualize your project's history.

Git Terminology
Branch
A branch is a version of the repository that diverges from the main working project.
Checkout
In Git, the term checkout is used for the act of switching between different versions of a target entity. The git checkout command is used to switch between branches in a repository.
Cherry-Picking
Cherry-picking in Git is meant to apply some commit from one branch into another branch. In case you made a mistake and committed a change into the wrong 
branch, but do not want to merge the whole branch. You can revert the commit and cherry-pick it on another branch.
Clone
The git clone is a Git command-line utility. It is used to make a copy of the target repository or clone 
Fetch
It is used to fetch branches and tags from one or more other repositories, along with the objects necessary to complete their histories.
HEAD is the representation of the last commit in the current checkout branch. We can think of the head like a current branch. 
Index
The Git index is a staging area between the working directory and repository.
Upstream and Downstream
The term upstream and downstream is a reference of the repository. Generally, upstream is where you cloned the repository from (the origin) and downstream is any project that integrates your work with other works. 
Master
Master is a naming convention for Git branch. It's a default branch of Git. After cloning a project from a remote server, the resulting local repository contains only a single local branch.
Merge
Merging is a process to put a forked history back together. The git merge command facilitates you to take the data created by git branch and integrate them into a single branch.
Origin
In Git, "origin" is a reference to the remote repository from a project was initially cloned. 
Pull/Pull Request
The term Pull is used to receive data from GitHub. It fetches and merges changes on the remote server to your working directory.
Push
The push term refers to upload local repository content to a remote repository. Pushing is an act of transfer commits from your local repository to a remote repository.
Rebase
In Git, the term rebase is referred to as the process of moving or combining a sequence of commits to a new base commit.
Remote
In Git, the term remote is concerned with the remote repository. It is a shared repository that all team members use to exchange their changes.
Repository
In Git, Repository is like a data structure used by VCS to store metadata for a set of files and directories.
Stashing
Sometimes you want to switch the branches, but you are working on an incomplete part of your current project. You don't want to make a commit of half-done work. Git stashing allows you to do so.
Tag
Tags make a point as a specific point in Git history. It is used to mark a commit stage as important. 
Git Revert
In Git, the term revert is used to revert some commit. 
Git Reset
In Git, the term reset stands for undoing changes. The git reset command is used to reset the changes.
Soft
Mixed
Hard
Git Ignore
the term ignore used to specify intentionally untracked files that Git should ignore. 
Git Diff
When it is executed, it runs a diff function on Git data sources. These data sources can be files, branches, commits, and more. It is used to show changes between commits, commit
Git Cheat Sheet
A Git cheat sheet is a summary of Git quick references. It contains basic Git commands with quick installation. A cheat sheet or crib sheet is a brief set of notes used for quick reference.
Git Flow
is a branching model for Git, this is a collection of Git commands. It accomplishes many repository operations with just single commands.
Git Squash
is used to squash previous commits into one.  Git squash is an excellent technique to group-specific changes before forwarding them to others.
Git Rm
the term rm stands for remove. It is used to remove individual files or a collection of files. 
Git Fork
A fork is a rough copy of a repository. Forking a repository allows you to freely test and debug with changes without affecting the original project.

Basic Git Command
Git Config 
Git init 
Git clone 
Git add
Git commit 
Git status 
Git push 
Git pull
Git Branch 
Git Merge 
Git log 
Git remote

Staging and Commit
"Staging" and "commit" are terms commonly associated with version control systems, especially Git.
Staging:

In Git, staging is the process of preparing changes for a commit. When you make modifications to your code or files, Git allows you to selectively choose which changes to include in the next commit.
Before a commit, you can use the git add command to stage specific files or changes. This means you're telling Git that you want these changes to be part of the next commit.
Staging is an intermediate step between modifying files and making a commit. It allows you to review and organize your changes before they become a permanent part of your version history.
Commit:

A commit is a snapshot of the changes you've made to your code at a specific point in time. It's a way to record the state of your project and is a fundamental operation in Git.
When you commit changes, Git stores a new commit object that contains a reference to the snapshot of the changes, a timestamp, the author's information, and a pointer to the previous commit. This forms a chain of commits, creating a version history for your project.
The git commit command is used to create a new commit.

Inspect and Undo changes
Git log
The advantage of a version control system is that it records changes. These records allow us to retrieve the data like commits, figuring out bugs, updates. But, all of this history will be useless if we cannot navigate it.
Basic Git log
Git log command is one of the most usual commands of git. It is the most useful command for Git. Every time you need to check the history, you have to use the git log command.
Git Log Stat
The log command displays the files that have been modified. It also shows the number of lines and a summary line of the total records that have been updated.
Git Checkout
In Git, the term checkout is used for the act of switching between different versions of a target entity. The git checkout command is used to switch between branches in a repository. Be careful with your staged files and commits when switching between branches.
Operations on Git Checkout
We can perform many operations by git checkout command like the switch to a specific branch, create a new branch, checkout a remote branch, and more. The git branch and git checkout commands can be integrated.
Checkout Branch
To switch between branches, use the below command.
The git checkout commands let you create and switch to a new branch. You can not only create a new branch but also switch it simultaneously by a single command.

Collaborating
Collaborating in git git refers to sharing on code among several developers

Git Fetch
Git "fetch" Downloads commits, objects and refs from another repository. It fetches branches and tags from one or more repositories. It holds repositories along with the objects that are necessary to complete their histories to keep updated remote-tracking branches.We can fetch the complete repository with the help of fetch command from a repository URL like a pull command does. See the below output:
$ git fetch< repository Url>

Git Pull / Pull Request
The term pull is used to receive data from GitHub. It fetches and merges changes from the remote server to your working directory. The git pull command is used to pull a repository. Pull request is a process for a developer to notify team members that they have completed a feature. Once their feature branch is ready, the developer files a pull request via their remote server account.

The "git pull" command
The pull command is used to access the changes (commits)from a remote repository to the local repository. It updates the local branches with the remote-tracking branches. Remote tracking branches are branches that have been set up to push and pull from the remote repository. Generally, it is a collection of the fetch and merges command.

Git Pull Remote Branch
Git allows fetching a particular branch. Fetching a remote branch is a similar process, as mentioned above, in git pull command. 
$ git pull <remote branch URL> 

Git Push
The push term refers to upload local repository content to a remote repository. Pushing is an act of transfer commits from your local repository to a remote repository. Pushing is capable of overwriting changes; caution should be taken when pushing.

Git Push Tags
<repository>: The repository is the destination of a push operation. It can be either a URL or the name of a remote repository.
<refspec>: It specifies the destination ref to update source object.

Git Force Push
The git force push allows you to push local repository to remote without dealing with conflicts. It is used as follows:
$ git push <remote><branch> -f OR $ git push <remote><branch> -force

