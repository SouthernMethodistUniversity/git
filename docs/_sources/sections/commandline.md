# Review of the Command Line (Optional Review)

During this workshop, you'll be communicating with GitHub from your local computer via the command line (the Terminal or the Git Bash on Windows). This section reviews some of the basic commands that will also be used in this workshop.

In addition to the command line, you'll be using your text editor and your browser. Before continuing, its important that we clearly distinguish between these three different spaces or environments:
- Your plain text editor where you'll be writing your syllabus is on your local computer.
- That syllabus is initially saved in a git-enabled repository on your local computer.
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
---



