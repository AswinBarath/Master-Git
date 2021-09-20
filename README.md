# Master Git

Master the concepts of Git with me through a set of tutorials


---


## What is Git ?

- Distributed Version Control System


## What is GitHub ?

- A GUI for hosting the Git folders/repositories/projects online to share, collaborate and contribute from around the world
- Other Platforms: BitBucket, GitLab

---


## Why are we using Git and GitHub?

- Maintaining the history of the project versions
- To track changes made by each person
- Share the project around the world


---


## Download Git

- [Git for macOS, Windows, Linux/Unix](https://git-scm.com/downloads)


---


## Basic Linux commands

- `ls`
	- Lists all the files and folders at present directory
- `ls -a`
	- Lists all the hidden files and folders as well
- `ls .git`
	- Lists all the files and folders inside `.git` folder
- `mkdir project`
	- Create a folder named *project*
- `cd project`
	- Changes directory to *project* folder
- `touch names.txt`
	- Create a file named *touch.txt*
- `vi names.txt`
	- Opens the vim editor for names.txt file
- `cat names.txt`
	- Displays all the content in names.txt file

---


## Where does Git store information ?

- The information like history, versions and so on are stored in another folder that git provides us.
- This is known the git repository
- This folder is named *.git*
- In Linux file systems, the folders preceded with `.` are hidden


---


## How does Git store information ?

- At its core, git is like a key value store.
- The Value = Data
- The Key = Hash of the Data
- You can use the key to retrieve the content.

---


## Git Commands

- `git init`
	- Initializes empty git repository in the current working directory
- `git status`
	- Know more about the changes made in the project
- `git names.txt`
	- Adds *names.txt* file to the staging area
- `git add .`
	- Add all of the files in the staging area
	- `.` means add all of the files/folders
- `git commit -m "names.txt file added"`
	- Commit all the files 
	- `-m` means to provide a message to the commit
- `git restore --staged names.txt`
	- Restores the changes made since previous commit from the staging area
- `git log`
	- Displays the entire history of commits

--- 


## Analogy to understand Git

- Consider a scenario of a wedding
	- 1 The Guests go the stage
	- 2 Photographer takes their picture with the couple
	- 3 The photos are saved in a wedding album
- Now, assume that the guests who have not taken their picture with couple yet as the **Untracked files**
- 1 Hence we take their picture by bringing them to stage => The untracked files are added to the staging area
- Now, we need to permanently save the picture in history
- 2 Hence the photographer takes their picture with the couple => The staged files 



## Source

- [Complete Git and GitHub Tutorial](https://youtu.be/apGV9Kg7ics) by Kunal Kushwaha <https://github.com/kunal-kushwaha>
- [Front end Masters - Git in-depth](https://frontendmasters.com/courses/git-in-depth/) by Nina Zakharenko <https://github.com/nnja>