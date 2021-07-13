# What is Git?

### The most widely used version control system is Git. Git keeps track of the changes you make to files so you can see what you've done and go back to previous versions if you need to. Git also facilitates cooperation by allowing many people's contributions to be merged into a single source.

### Whether you develop code that will only be seen by you or work as part of a team, Git will be beneficial to you.

![What is Git](https://www.nobledesktop.com/image/blog/git-branches-merge.png)


**Git is a piece of software that runs on your computer. Your computer saves your data and their history. You can also save a copy of the files and their modification history on internet servers (such as GitHub). You can work more readily with other developers if you have a central location where you can submit your modifications and get changes from others. Git can merge changes automatically, so two individuals may work on separate portions of the same file and then combine their changes without losing each other's work!**


- **Local Operations:**

**Git mostly relies on local operations because most necessary information can be found in local resources. This allows for process expediency because a project’s history resides on the local disk, eliminating the need to fetch history information from the server, and allowing one to continue work on a project even when not online or on a VPN.**

- **Tracking Changes:**

**Every single change applied to any file or directory is tracked by Git. And, as the gatekeeper, Git will always detect file corruption or loss of information in transit.**

- **Loss of Data:**

**Git is set up to greatly minimize the possibility of irreversible damage to files, such as accidentally lost data. Git makes it extremely difficult for a snapshot of your file that is committed to be lost.**

- **States:**

**Files in Git can reside in three main states: committed, modified and staged.**

- **Committed:**

**Data is securely stored in a local database.**

- **Modified:**

**File has been changed but not committed to the database.**

- **Staged:**

**Flagged a file’s changed version to be committed in the next snapshot.**

***

![how it's working](https://blog.udemy.com/wp-content/uploads/2015/08/image066.png)

***

|Advantages of Git|
|--------------|
|1. Good distributed model as each developer gets a local repository with a full history of commits which makes git fast compared to other VCs.|
|2. Branching capabilities and merging are easy (as they are cheap), good data integrity.|
|3. Data redundancy and replications. Add ons can be written in many languages.|
|4. The object model is very simple and minimizes push/pull data transfers.|
|5. The push/pull operations are faster with a simple They save time and developers can fetch and create pull requests without switching.|

***

# Getting Started


**Download Git**

#### In order to use Git, your computer must have it available. If you already have Git on your computer, you should make sure you have the latest version.

### Git can be installed in three ways:

1. Install as a package
2. Install via another installer
3. Download and compile the source code.


+ ## Windows

#### Git Website 

### You can download Git by visiting this link and following the posted directions:

[http://git-scm.com/download/win](http://git-scm.com/download/win)

**GitHub**

### Install Git as part of the GitHub for Windows install.

[http://windows.github.com](http://windows.github.com)


+ ## Linux

**Package Manager**

### You can try installing Git via your distribution’s inherent package management tool.

**For Fedora:**

> `$ sudo yum install git`

**For Ubuntu:**

> `$ sudo apt-get install git`

**Git Website**

### To download Git for Linux, visit this link and follow the posted directions:

[http://git-scm.com/download/linunx](http://git-scm.com/download/linux)


# To know more settings and features click on the link

- [Git Intro](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/)

***

# Cloning

### You can also create a copy of an existing Git repository from a particular server by using the clone command with a repository’s URL: 

> `$ git clone https://github.com/test`

**By cloning the file, you have copied all versions of all files for a project. This command leads to the creation of a directory called “test,” with an initialized .git directory inside it, which has copies of all versions of all files for the specified project. The command also automatically checks out — or retrieves for editing — a copy of the newest version of the project.**

**To clone a repository into a directory with another name of your choosing, use the following command format:**

> `$ git clone https://github.com/test mydirectory`

**The command above makes a copy of the target repository in a directory named "mydirectory."**

***

# The Life Cycle of File Status

![File Status](https://blog.udemy.com/wp-content/uploads/2015/08/image006.png)

***


# resources

+ [Git Intro](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/)
- [Advantages](https://www.educba.com/introduction-to-git/)
