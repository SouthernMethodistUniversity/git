# Command Line

# The Unix shell

Shell: ["A shell is a terminal application used to interface with an operating system through written commands." ](https://www.atlassian.com/git/tutorials/git-bash#:~:text=Git%20Bash%20is%20an%20application,operating%20system%20through%20written%20commands.)
- The [Unix shell](https://swcarpentry.github.io/shell-novice/01-intro.html) is both a command-line interface (CLI) and a scripting language, allowing such repetitive tasks to be done automatically and fast. 
- The most popular Unix shell is Bash. Bash is the default shell on most modern implementations of Unix and in most packages that provide Unix-like tools for Windows. Note that ‘Git Bash’ is a piece of software that enables Windows users to use a Bash like interface when interacting with Git.

# Bash

- "Bash is a popular *default shell* on Linux and macOS. Git Bash is a package that installs Bash, some common bash utilities, and Git on a Windows operating system."
- If you are running Linux and macOS, Bash should be available.  If you are running Windows, you need to install GitBash. 
- [Installation](https://carpentries.github.io/workshop-template/install_instructions/#shell)

- Based on [Software Carpentry lesson](https://swcarpentry.github.io/shell-novice/) 
- [What is Terminal, Console, Shell and Kernel?](https://www.geeksforgeeks.org/what-is-terminal-console-shell-and-kernel/)

# Review of Command Line 

We will begin with an overview of the Command line (also command shell).
- For additional practice, you can look at this [The Unix Shell workshop](https://swcarpentry.github.io/shell-novice/index.html)


## Review of the Command Line

During this workshop, you'll be communicating with GitHub from your local computer via the command line (the Terminal or the Git Bash on Windows). This section reviews some of the basic commands that will also be used in this workshop.

In addition to the command line, you'll be using your text editor and your browser. Before continuing, its important that we clearly distinguish between these three different spaces or environments:
- Your plain text editor where you'll be writing your document is on your local computer.
- That document is initially saved in a git-enabled repository on your local computer.
- Your browser is where you'll be uploading your repository to GitHub, a cloud service.
- Your terminal is where you'll be communicating with GitHub to send the repository and project files back and forth between the cloud (which you can view through the GitHub website) and your hard drive.

Because you'll be moving between these three spaces throughout the workshop, you may want to use (<kbd>command (⌘)</kbd> + <kbd>tab</kbd>) or (<kbd>control</kbd> + <kbd>tab</kbd>) to move quickly between the three windows on your desktop.

## Accessing the Terminal

### macOS

Hold the <kbd>command (⌘)</kbd> key and press the <kbd>space</kbd> bar at the same time to bring up the "Spotlight Search" window. Type `terminal`, followed by <kbd>enter</kbd> to quickly open the Terminal.

### Windows

Press the <kbd>windows</kbd> button on your keyboard. When the search menu pops up, type `git bash` and press <kbd>enter</kbd>.

## Practice Navigating the Command Line

If you don't feel comfortable navigating your hard drive through the command line, here is a short section catching you up. 
- _If you feel fairly comfortable using the command line, you can skip this ._
- If you _do not have experience or prior knowledge of the command line, you may want to work through one of 
 the following workshops_: [Introduction to the Command Line](https://gc-dri.github.io/Dhrift-GC/workshops/command-line/) or [The Unix Shell](https://swcarpentry.github.io/shell-novice/)

You can create the folder anywhere on your hard drive by typing the following into your terminal and hitting <kbd>enter</kbd>.

```console
$ cd <directory-name>
```

Let's practice this command by using it to take us to our Desktop. Type the following command into your terminal and hit <kbd>enter</kbd>.

```console
$ cd Desktop
```

This will change your current working directory from `/Users/<your-name>` to `/Users/<your-name>/Desktop`.

#### *Note for staff or company computers* 

If your computer has multiple users you can choose your user profile in the C: drive or you type the following command in your terminal and and hit <kbd>enter</kbd>
```console
$ cd C:/Users/[put your username such as SMU ID here]/Desktop/
```



Check your current directory by typing the following command into your terminal and hit <kbd>enter</kbd>:

```console
$ pwd
```

Now, use the following command to go up one directory:

```console
$ cd ..
```

Check your current directory again using the following command. You should be back in your "home" directory:

```console
$ pwd
```

Practice going back and forth between your Desktop and your home directory.

When finished, go to your Desktop folder and check that you're there with `pwd`.

## Making a Projects Folder

In this session, we will be making a syllabus and using Git to keep track of our revisions. Let's create a Git project folder.

If you don't have a projects folder on your desktop, create one using the following command:

```console
$ mkdir projects
```

From `Desktop`, Navigate into your `projects` folder using the following command:

```console
$ cd projects
```

Then create a `git-practice` folder with the following command:

```console
$ mkdir git-practice
```

Navigate into the new `git-practice` folder using the following command:

```console
$ cd git-practice
```

At this point, when you type `pwd`, your folder structure should look like this:

```console
$ pwd
/home/<username>/Desktop/projects/git-practice
```

TO see what files are in a folder, `ls`, it will show what files are there. To see all files, including invisible, type `ls -a`

```console
$ ls

$ ls -a
```



***Authenticating to Remote Git Repositories***  
"Git provides multiple protocols for authenticating to and interacting with remote Git repositories. 
  
There are three main approaches you can take:
- Using a personal authentication token or password
- Using an SSH key
- Using your GitHub password with 2-factor authentication"
- [See these directions from Berkeley Statistics](https://statistics.berkeley.edu/computing/faqs/git-auth)
    - For additional directions, [see Github's Authentication documentation](https://docs.github.com/authentication)


## Evaluation

Which command do you use to make a new folder?
- `pwd`
- `cd`
- `mkdir`*

Which command do you use to enter into a folder?
- `pwd`
- `cd`*
- `mkdir`

Which command do you use to check where you are?
- `pwd`*
- `cd`
- `mkdir`


## Pro-tip for the Command Line: How to exit unknown screens

If you're ever stuck or "trapped" on the command line, try running through these common exit commands to return to the prompt:

- <kbd>control</kbd> + <kbd>c</kbd>
- <kbd>control</kbd> + <kbd>d</kbd>
- `q` followed by <kbd>enter</kbd>
- `:q` followed by <kbd>enter</kbd>

<kbd>control</kbd> + <kbd>c</kbd> attempts to abort the current task and restore user control. <kbd>control</kbd> + <kbd>d</kbd> escapes the current shell environment—if you use it at the normal `$` prompt, it will end the current command line session. `q` is often used as a command (followed by <kbd>enter</kbd>) to escape from specific programs like `less`. `:q` is the command used in `vi` that changes the mode of interaction (`:`), allowing you to enter the `q`, a one-letter command to quit, which must be followed by <kbd>enter</kbd>. Thus, it's a command specific to `vi`.



## Evaluation

Which best describes where you are working when you're writing in your plain text editor:
- on my local machine*
- on the internet

Which best describes where you are working when you're using your terminal to communicate with GitHub and share the files:
- on my local machine*
- on the internet

Which best describes where your files are when you are viewing them in GitHub:
- on my local machine
- on the internet*

Git-enabled repository means
- none of the files on my local machine are being tracked
- a specific file on my local machine is being tracked
- a specific folder on my local machine is being tracked*
- all the files on my local machine are being tracked

Which command do you use to make a new folder?
- `pwd`
- `cd`
- `mkdir`*

Which command do you use to enter into a folder?
- `pwd`
- `cd`*
- `mkdir`

Which command do you use to check where you are?
- `pwd`*
- `cd`
- `mkdir`
---
 ## Shell Cheat Sheets

[Summary of Basic Commands](https://swcarpentry.github.io/shell-novice/reference.html#summary-of-basic-commands)

| Action       | Files | Folders      | 
| ------------ | ----- | ------------ |
| Inspect      | ls    | ls           | 
| View content | cat   | ls           | 
| Navigate to  |       | cd           | 
| Move         | mv    | mv           | 
| Copy         | cp    | cp -r        | 
| Create       | nano  | mkdir        | 
| Delete       | rm    | rmdir, rm -r | 

- [Unix Shell Cheat Sheet](https://cambiotraining.github.io/hpc-intro/99-unix_cheatsheet.html)

## Glossary
- [Glossary](https://swcarpentry.github.io/shell-novice/reference.html#glossary)

