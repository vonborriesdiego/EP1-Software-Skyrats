# EP1-Software-Skyrats
First EP as a skyrats software fellow. Create a README explaining the first workshop.

## LINUX, GIT e GITHUB

![download](https://github.com/vonborriesdiego/EP1-Software-Skyrats/assets/77511058/91603cb2-e05f-4b08-ba71-ca737d1dcf14)

## Linux
* Often referred as an operating system, but strictly speaking, it is a Kernel. <br> 
*Kernel:* Core component of an operating system and serves as the main interface between computer's hardware and the process running on it. <br>
* Low level (C and Assembly). <br>
* In the 80s, thanks to Richard Stallman GNU project could accomplish his goal of making an operating systen that was freely to everyone, and where everyone could work together. <br>
* In the 90s, to be more specific 1991, Linus Torvalds, a Swedish student put his source code online; a brand new POSIX compilant kernel; online. Many people embraced the combination of this kernel with the GNU tools.

### Distributions 
* Is a collection of (usually open source) software on top of a Linux kernel. <br>
* A distribution (or short, distro) can bundle server softwar, system management tools, documentation and many desktop applications in a central secure software reopsotory.
* A distro aims to provide a common look and feel, secure and easy software management and often a specific operational purpose. <br>

### Debian
* Basis of every Ubuntu release. 
* Seen as one of the most stable Linux distributions.
* Stable root distribution.
* *Ubuntu:* Versions long term support.
* *Linux Mint:* Performance set for casual uses.
* *Linux Lite:* Simple and easy to use.
* Fun fact: Every Debian release is named after a character in the movie Toy Story.
<img width="676" alt="historydebian" src="https://github.com/vonborriesdiego/EP1-Software-Skyrats/assets/77511058/1b34dca0-5161-484d-9c64-62564f545ed2">

### Arch
* Highly customizable.
* *Manjaro:* Privacy and highly control.

### Gentoo
* Accuracy and optimization on compilation task.

### Fedora
* Usability and freedom.

### Which one to use?
* Depends on the needs of the user. 
<img width="768" alt="Screen Shot 2023-05-10 at 9 18 29 AM" src="https://github.com/vonborriesdiego/EP1-Software-Skyrats/assets/77511058/307c4ab0-33e8-41df-af04-8f5fa1b41e47"> <br> 
*Note.* Table took from *Linux Fundamentals by Paul Cobbaut.*

### Files System
* Linux inherited the Filesystem Hierarchy (FHS) Standard from UNIX.
* The FHS may help make more Unix/Linux file system trees conform better in the future.
* To make it simpler, a FHS is how drives, folders, files, and other storage devices are organized and displayed on an operating system.
* In a hierarchical file system, the drives, folders, and files are displayed in groups, which allows the user to see only the files they're interested in seeing.
* People should be aware of allowing to modificate some protected directories.
* In Linux, everything is a file.

### Access permissions 
* Read *-r*
* Modify *-w*
* Execute *-x*

### *Sudo* Command 
* Accessing directories, functions and protected files.

### User directory
* **/home**

### Protected Directories
* **/root** and **/sys**
* **/bin** and **/sbin**
* **/boot** and **/run**
* **/usr /media /mnt**
* **/lib /lib32**
* **/lib64**

### Terminal Command 
* Full system control.
* Command format: **[function]** **[flag]** **[argument]**
* **-h** **mkdir -help**
* *ls* - Visualize directory files.
* *cd/path* - Access to a directory.
* *mkdir [name]* - Create a new directory.
* *touch /path* - Create a file.
* *rm -r/path* - Remove a directory with all the files.
* *sudo apt update* - Update a  package.
* *sudo apt install [package]* - Install packages.

### Git 
* Distribuited Version Control System.
* *Code versioning* - Records all changes and allows redirect all versions.
* *Allows working in group* - Clone the project, add changes, mix changes.

### Git Fundamentals
* **Repository:** Directory with all files and changes.
* **Branch:** Independent copy of the main repository.
* **Merge:** Mix changes from different branches.
* **Fork:** Copy of a repository directly tied to the usser personal account. so the user can work on a copy of an original project.
* Keeps a local copy of the project with all the files and changes.
* *Commit* - command used to keep the changes.
* It is possible the use of branches to meake changes without affecting the main code.
* Once the changes are commited, the user can update the changes on a remote repository, so the members can have access.
* Members can pull and copy the changes to their local repositories.
* Members can also merge their alterations with yours.

![download](https://github.com/vonborriesdiego/EP1-Software-Skyrats/assets/77511058/ad0cc1a2-3d4d-40cc-bd88-58aa1f0fb518)


### GITHUB
* Online platform based on Git.
* Project storage.

### Commands
* **git init:** Initialize a new empty Git repo.
* **git clone:** Clone a remote Git repo.
* **git add:** Add files to be tracking by Git.
* **git commit:** Save all changes in one or more files on a remote repo.
* **git push:** Sends changes from a local repo to a remote repo.
* **git pull:** Pull changhes from a remote repo to a local repo.
* **git branch:** Create, list or exclude branches.
* **git merge:** Combine changes from two or more Git branches.
* **git status:** Show the actual local repository status.

### GITIGNORE
* Specifies intentionally untracked files that Git should ignore.
* We must create a file named ".gitignore" on the root of the project.
* List all the files and folders to be ignored.
* Ignores sensitive files (passwords, user personal info).
* Ignores unnecessary files (images, proves).

![download](https://github.com/vonborriesdiego/EP1-Software-Skyrats/assets/77511058/1b9ae90e-a491-46fb-aec3-6261d6d44225)

### Commits
* We use commit when we want to perform logic changes.
* Change and perform successful tests.
* Clone and test.
* Messages are usually in english.
* Present tense verb or imperative.
* Use Gitmoji to indicate an action.

### README 
* Informative file that shows up after accessing a repo.
* Got useful information about the project (goals, installation, perform guide).

![download](https://github.com/vonborriesdiego/EP1-Software-Skyrats/assets/77511058/1e6c8e69-89fa-429b-b4b9-35a18036de2c)
