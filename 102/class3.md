# Git/Github

## Version Control

*What is version control?*

+ Version Control is a system that allows you to revisit various versions of a file or set of files by recording changes.
  - Through version control, one can revert a file or project to a previous version, track modifications and modifying individuals, and compare changes. By utilizing a Version Control System (VCS), mistakes with files can easily be rectified.
+ A local version control system is a database on your hard disk that stores changes to the files.
+ A Distributed Version Control systems (DVCS) addresses the major vulnerability of the CVS: the server as a single point of failure. If a CVS goes down, collaborators cannot work with each other on a file or save changes and new versions. Also, in the event of corruption of a central database’s hard disk — with the absence of backups — all work will be lost, except for any portions on local machines.
  - To prevent this type of catastrophic loss, a DVCS allows clients to create mirrored repositories. These data backups can be easily be placed on the server to replace any lost information.
  - Because the DVCS allows for multiple mirrored repositories, programmers working in teams can collaborate with each other in various ways to complete a joint project, which enables the use of various simultaneous workflows.

*What is Git?*

__*Snapshots*__

Git is a DVCS that stores data in a file system made up of snapshots. Each time you save a changed version of your project — called commit — Git creates a snapshot of the file and stores a reference to it. If the file has not changed, Git only stores a reference to the already-stored identical version of it.

__*Local Operations*__

Git mostly relies on local operations because most necessary information can be found in local resources. This allows for process expediency because a project’s history resides on the local disk, eliminating the need to fetch history information from the server, and allowing one to continue work on a project even when not online or on a VPN.

__*Tracking Changes*__

Every single change applied to any file or directory is tracked by Git. And, as the gatekeeper, Git will always detect file corruption or loss of information in transit.

__*Loss of Data*__

Git is set up to greatly minimize the possibility of irreversible damage to files, such as accidentally lost data. Git makes it extremely difficult for a snapshot of your file that is committed to be lost.

__*States*__

1. Committed - Data is securely stored in a local database
2. Modified - File has been changed but not committed to the database
3. Staged - Flagged a file's changed version to be committed in the next snapshot

## Customization

Terminal commands:

Identity

> git config --global user.name "Jane Smith"

> git config --global user.email "example@email.com"

Global applies Git settings to anything on the system.

Default Text Editor (EMacs example)

> $ git config --global core.editor emacs

Check Settings

> git config --list

Help, Manual

> git help command

> git command --help

> man git-command

## Setting Up a Git Repository

To import an existing project or directory into Git, follow these steps using the Terminal or Command Line:

1. Switch to the target project’s directory

Example:

> $ cd test (cd = change directory)

2. Use the git init command

> $ git init

Note: At this stage, you have created a new subdirectory named .git that has the repository files. Tracking has not commenced.

3. To start tracking these repository files, perform an initial commit by typing the following:

> $ git add *.c

> $ git add LICENSE

> $ git commit -m “any message here”

Now, your files are tracked and there’s an initial commit.

## Cloning

You can also create a copy of an existing Git repository from a particular server by using the clone command with a repository’s URL:

> $ git clone https://github.com/test

By cloning the file, you have copied all versions of all files for a project. This command leads to the creation of a directory called “test,” with an initialized .git directory inside it, which has copies of all versions of all files for the specified project. The command also automatically checks out — or retrieves for editing — a copy of the newest version of the project.

To clone a repository into a directory with another name of your choosing, use the following command format:

> $ git clone https://github.com/test mydirectory

The command above makes a copy of the target repository in a directory named “mydirectory.”

## Workflow

The local Git repository has three components:

1. Working Directory: Files reside here
2. Index: Area used for staging
3. Head: Points to the most recent commit

## Saving Changes

+ Tracked files can be modified, unmodified, or staged; they were part of the most recent file snapshot.

+ Untracked files were not in the last snapshot and do not currently reside in the staging area.

+ You can check the state of files using the **git status** command.

## Tracking and Staging a New File

__*Single File*__

> git add filename

__*All Files*__

> git add .

> git add *

__*Check Status*__

> git status

## Committing a File

> git commit -m "made change x,y,z"

## Committing All Changes

> git commit -a

## Pushing Changes

> git push origin main

> git push origin master