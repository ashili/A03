
- ![#1589F0](https://placehold.it/15/1589F0/000000?text=+)# A03



Learn Github By Anis Shili

## **GIT**

Git is a version control system. It helps you control the different versions of the files in your project.

The collection of all the old versions of your project's files is known as a Git repository.

Each time you complete a change to some or all of your project's files, you can take a snapshot of their current contents. These snapshots are known as commits.

Git is a distributed version control system, as opposed to a centralized system. In a distributed system, you can copy a complete repository with the full project history to every developer's machine.
Bash is a command shell that runs on many Mac, Linux, and even some Windows computers when you open their terminals.
Bash prompts usually end in a dollar sign. When you read Git tutorials out on the web, you may see a dollar sign; that usually indicates that the text following it should be typed at a shell prompt.
When Git is installed on a system, like it is here in this workspace, it places an executable named git where it can be run from any shell prompt. This is the git command.

All the commands with git followed by a space.
Then you need to specify the subcommand or options we want.
Git command line options consist of either a single dash followed by a single letter, or a double-dash [type --] followed by a word.
*exp*: git --help will print out some help on using the Git program.

## **GITHUB**

By now you should know that you are in guthub and This is github.com

## **REPOSITORY**

It's basically just a folder in which you can edit your files, then run Git commands to store your changes


<h1 style="color:green"><b>GIT COMMANDS</b></h1>


## CREATION
to create a repository you can use the init to create a new repo or clone to get a pre-create one.

<h3 style="color:red">init</h3>

git init command is used to set up new repository.

You need to go the folder you want to put in github and use the following command

```bash

git init

```

or

<h3 style="color:red">clone</h3>



it downloads the repository in whatever specified folder.

```bash

git clone https://github.com/your username/repository name.git
```

## LOCAL CHANGES

### status

shows the infomation about the status of the changed files in the reposirory

```bash

git status

```

### Commit

it is used to save changes. Extra flags may be added to the commit subcommand such as

* -m for entering a message to mark the changes or information about that change

```bash

git commit -m "your message here"

```

## add

add new changed files to be commited. i used with "." it will add all changed files to the next commit.

```git

git commit -m "your message here"

```

## Push

push the changes to the master repository. -u will prompt you for a username

```bash

git push -u origin master

```

## Pull

pull changes from the repository

```git

git pull
```



## Branch

branch command is used with flags to help you managing your branches inside the repository

exp:

to list all existing branches use

```git

git branch -av
```

to create a newe branch use

```git

git branch "your new branch"

```

# MERGE

## merge
to merge a branch into current HEAD.

```git

git merge "branch name"

```

## Merge Conflict

# UPDATE

## Fetch

download all the changes from the remote but doesnt integrate into HEAD.

```git

git fetch "remote name"

```

## Remote

*-v will list all currently configured remotes

```git

git remote -v

```
