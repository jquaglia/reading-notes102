# Git and GitHub

## Version Control

Version Control is a system that allows you to revisit old versions of a file or set of files.

### Local Version Control

Local VCS entails one database on the hard disk that stores changes to files.

### Centralized Version Control

Centralized version control arrose with the need for a team to collaborate on a single project. This system has a single server storing all changes and file versions. This helped to streamline collaboration process.

### Distributed Version Control

DVCS addresses the one weakness of CVS which is if the server itself fails. DVCS allows clients to create mirrored repositories. These backups can be easily replaced if another gets corrupted. This also means many collaborators can work at the same time on the same file.

## Git

### Snapshots

Git is a DVCS that stores files in a system of snapshots. Every time you save (or commit) a version of your project, Git creates a snapshot of the file.

### Local Operations

Git relies mostly on local operations. This helps productivity because a projects history resides on the local disk which means you don't have to fetch project history from the server.

### Tracking Changes

Every single change applied to any file or directory is tracked by Git. Git will also detect file corruption or loss of information in transit.

### Loss of Data

Git is set up to minimize the chance of loss of data or irreversible damage to files. it is extremely difficult for a snapshot that has been committed to be lost.

### States

#### Committed

Data is securely stored in local database.

#### Modified

File has been changed but not committed to the database

#### Staged

Flagged a file's changed version to be committed in the next snapshot.

## Brief History

The creators of Linux used to use a different DVCS but weren't happy with it. Linus Torvalds began creating Git to replace it. Since 2005 with it's inception, Git is the most used VCS in the world.

## Terminal Commands for git help

- git config --list

- git help command

- git command --help

- man git-command

### Importing

- cd to target project's directory

- git init command (creates a new subdirectory named .git)

- git add *.c (to start tracking these files)

- git add LICENSE

- git add commit -m "any message here"

### Cloning

You can also create a copy of an existing Git repo by using the clone command with repo's URL.

- git clone "https://github.com/test"

To clone a directory into a directory with another name use the following

- git clone "https://github.com/test" mydirectory

## Local Repo Structure

1. Working Directory: Actual files reside here
1. Index: The area used for staging
1. Head: Points to the most recent commit

## Saving Changes

### Tracked

Tracked files can be modified, unmodified, or staged. Part of the most recent snapshot.

### Untracked

Untracked files were not in the last snapshot and are not in the staging area. *After you clone a repo, files have tracked status and are unmodified because they have been checked out but not edited.*

## The Life Cycle of File Status

1. After you edit a file, Git flags it as modified
1. You stage the modified file
1. Then, you commit the changes

### Check File Status

to determine the state of files, use git status command

- git status

On branch master

nothing to commit, working directory clean *This info indicates which branch you're on and states that it is clean. This means that files are currently tracked or modified status. No untracked files are present becuase it has not listed any.*

### Tracking and Staging a New File

#### Single File

- git add filename

#### All Files

- git add *

### Commiting a File

After staging one or multiple files, you commit the changes and document what was done in the message

- git commit -m "made change x, y, z"

### Commiting All Changes

- git commit -a

### Pushing Changes

- git push origin master

*This will push changes from the local master branch to the origin repo*

### Stashing Changes

When you are not ready to commit changes but do not want to lose them either, the following command temporarily removes changes and hides them. This gives you a clean working directory.

- git stash

When you want to continue working on the changes use the following

- git stash apply





[back to README](README.md)
