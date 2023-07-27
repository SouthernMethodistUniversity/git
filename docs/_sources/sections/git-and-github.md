# Getting Started with Git and GitHub (Workshop)

**Git** is software used for version control—that is, tracking the state of files and changes you make to them over time. Git can be enabled in a folder, and then used to save the state of the contents in that folder at different points in the future, as designated by you. In the language of Git, a folder is called a _repository_. In the context of this workshop, it refers to a folder that is being tracked by Git. Using Git, you can view a log of the changes you've made to the files in a repository and compare changes over time. We will explore these features in the current workshop. You can also revert back to previous versions, and create "branches" of a project to explore different futures. These are advanced features, which we will provide resources for you to explore later. Git is also useful for collaboration, as a repository can be shared across computers, and its contents can be asynchronously developed and eventually merged with the main project.

**GitHub** is an online platform for hosting Git repositories. It functions for some, predominantly programmers, as a social network for sharing and collaborating on code-based projects. Users can share their own projects, as well as search for others, which they can then often work on and contribute to. Digital Humanists, librarians, and other academics are also finding ways Git and GitHub are useful in writing projects and teaching. GitHub also serves as a web-hosting platform, allowing users to create websites from their repositories.


## Highlighting Distinctions

As we move forward it's important to make sure we're firm on the distinctions between the three different tools outlined above.

**Git** is a software that you use on your laptop, or your local computer/machine. The repository with your project's files is stored on your hard drive. You also edit the text files on your local machine using a plain text editor, which is another software on your local computer like Visual Studio Code.

**GitHub** is a cloud-based platform that you access through your internet browser. Even though you physically are still in the same place, working on your laptop, you are no longer working on your local machine, you are on the Internet. This is a fundamentally different location than when you're working with your Git repository and editing and creating files in your plain text editor. With GitHub, you are uploading your repository—as described above—from your local machine to this platform on the Internet to be shared more broadly. You can also create private repositories if you want to use GitHub to backup a project.


# Why use it? What You Can Do with Git and GitHub ?

* <a href="https://github.com/SouthernMethodistUniversity/git/blob/main/sections/files/HPCgithubintro.pdf">Link to presentation slides</a>


## How We Use GitHub

### Collaborative Writing

Git is also used in writing projects! _Version control_ makes tracking changes trackable, especially when there are multiple authors working asynchronously. It can be an alternative to using track changes in Microsoft Word, or comments and edits in a Google Doc.

### Versions Across Time (Version control)

How did you initially come by the syllabus you use for your class(es), and did you develop it over time? Many professors borrow and adapt from each other, and most of us probably update our syllabi each semester, even if only a little bit.

Through this process, many of us end up with a set of files that looks something like this:

![Example of a messy folder structure with many files named similarly](../sections/images/messy-file-structure.png)
While I probably can tell which version is the "final" one, I can not see what was changed along the way or how the different versions vary from each other.

With Git, you would save these multiple versions over time as one file, and each version you save includes a note about what has changed so you can easily revert back to an older version if needed.

By looking at the file list, you also can not tell who the syllabus originally came from, or if there were contributions from many individuals. Git and GitHub can help make attribution clear, and maintain it over time as the syllabus travels between hands.

**Syllabi examples**
* Increasingly we see that faculty are sharing their syllabi on GitHub (example: [DLCL 204: Digital Humanities Across Borders](https://github.com/quinnanya/dlcl204)). Some are even using GitPages that apply a user-friendly interface to their repository to make it easier to access and navigate for their students (example: [Digital History](https://digitalhistory.github.io/)).

With version control:
- Nothing that is committed to version control is ever lost, unless you work really, really hard at it. Since all old versions of
  files are saved, it's always possible to go back in time to see exactly who wrote what on a particular day, or what version of a
  program was used to generate a particular set of results.
   - Teams are not the only ones to benefit from version control: lone researchers can benefit immensely.  Keeping a record of what was
changed, when, and why is extremely useful for all researchers if they ever need to come back to the project later on (e.g., a year later,
when memory has faded).
- As we have this record of who made what changes when, we know who to ask if we have questions later on, and, if needed, revert to a previous version, much like the "undo" feature in an editor.
- When several people collaborate in the same project, it's possible to accidentally overlook or overwrite someone's changes. The version control system automatically notifies users whenever there's a conflict between one person's work and another's.
- Version control is the lab notebook of the digital world: it's what professionals use to keep track of what they've done and to
collaborate with other people.  Every large software development project relies on it, and most programmers use it for their small jobs
as well.  And it isn't just for software: books, papers, small data sets, and anything that changes over time or needs
to be shared can and should be stored in a version control system.

<sub> [Click here for extended explanation of: What is version control](https://swcarpentry.github.io/git-novice/01-basics.html)</sub>

### Sharing and Attribution

As you can see [we use GitHub to host workshop curricula.](https://github.com/SouthernMethodistUniversity?q=git&type=all&language=&sort=) Hosting sessions on GitHub allows you (and anyone else interested in these topics!) to follow our repositories, and create your own version of the workshop based on our materials. This fosters open scholarship and knowledge sharing. It also facilitates attribution and citation by clearly tracking which content was created by whom, when it was added, and which projects or materials are derived from others.[As you can see in our acknowledgements](https://github.com/SouthernMethodistUniversity/git#acknowledgements)
- You can [add a citation file as well](https://swcarpentry.github.io/git-novice/12-citation.html)

---
* Github & Digital Humanities: A [study of how Digital Humanists use GitHub](https://digitalscholarship.files.wordpress.com/2016/07/spirosmithdh2016githubpresentationfinal.pdf), conducted by Lisa Spiro and Sean Morey Smith, found that a wide range of users, including professors, research staff, graduate students, IT staff, and librarians commonly used the site in their DH work. They used GitHub for a diverse range of activities, such as:

- Developing software
- Sharing data sets
- Creating websites
- Writing articles and books
- Collating online resources
- Keeping research notes
- Hosting syllabi and course materials


* Github & Open Science
- When version control is diligently, it acts as a shareable electronic lab notebook for computational work
- It helps make code citable 
- [Open scientific work](https://swcarpentry.github.io/git-novice/10-open.html)

---


# SET UP: Setting Up Git

Through this section, you'll be checking your installation and configuring Git with your own name and information.

## Check Your Installation

First, let's make sure [Git](https://git-scm.com/downloads) has been successfully installed. In your terminal, type the following command:

```console
$ git --version
```

If you see a version number, you're all set. If not, follow the installation instructions [here](https://gc-dri.github.io/Dhrift-GC/workshops/git/?page=5) or [here](https://swcarpentry.github.io/git-novice/index.html#installing-git).

## Configuring Git on Your Computer

Our first step in working with Git is letting the software know who we are so it can track our work and attribute our contributions. This information is useful because it connects identifying information with the changes you make in your repository.

Type the following _two commands_ into your command line, replacing the "John Doe" and "johndoe@example.com" with your name and email (use quotations where you see them). These do not necessarily need to be the name and email you used to sign up for GitHub. Remember, these are different spaces and different softwares.

```console
$ git config --global user.name "John Doe"
$ git config --global user.email johndoe@example.com
```

To check your set-up, type the following command into your terminal:

```console
$ git config --list
```

You should get something that looks like this except with whatever information you entered previously:

```
user.name=Superstar Git User
user.email=gitsuperstar@gmail.com
```

<sub> [More about setting up git](https://swcarpentry.github.io/git-novice/02-setup.html)</sub>

---

# Creating a Syllabus File

The next step is to _initialize_ the project folder that we want Git to track. Even though we configured Git for our computer, Git doesn't start tracking every single file on our computer. That would turn into a headache quickly. We only want Git to track changes for files within specific folders/projects.  

When we initialize a folder, we are telling Git to pay attention to it. This only needs to happen once because what is actually happening through this process is Git is adding a hidden subfolder within your folder that houses the internal data structure required for version control. After initialization, Git is ready to track the files within the folder. The folder is now considered a Git _repository_.

First, use `cd`, navigate to the `git-practice` folder (inside `projects`). From your home directory, you can do all of them in one command by typing the following into your terminal:

```console
$ cd Desktop/projects/git-practice
```

Next we're going to _initialize_ our repository using the `git init` command, which should generate the following output:

```console
$ git init
Initialized empty Git repository in /home/<your-username>/projects/git/.git/
```

Now Git is tracking our directory. However, it has not done any versioning yet. This is because 1) we haven't told Git to take a snapshot yet, and 2) there are no files in the folder to take a snapshot of. For now, Git knows this folder exists and is prepared to take a snapshot of the files when you tell it to.

Before version control is useful, we'll have to create a text file for Git to track. For this session, the file we will track will be a course syllabus—we'll create that next.

<sub>[More about creating a repository](https://swcarpentry.github.io/git-novice/03-create.html)</sub>


### Creating a Syllabus file

To create a plain text file, we're going to switch to our text editor, Visual Studio Code, to create and edit a file named `syllabus.md` and save it to our `git-practice` folder. The `.md` extension indicates that it is a Markdown file, which is a special file format we will dive into in the next section.  

If you have not installed Visual Studio Code, review [the installation instructions here](https://github.com/DHRI-Curriculum/install/blob/v2.0/guides/visual-studio-code.md).

In terminal, check to make sure you are in your `git-practice` folder. (_Hint_: use `pwd` to see what directory you are currently in.)

Next, open the `syllabus.md` file in Visual Studio Code using:

```console
$ code syllabus.md
```

You should see a window appear that looks similar to this:

![Image of what Visual Studio Code looks like when opening the syllabus.md file](../sections/images/vscode1.png)

If Visual Studio Code does not open when you use the `code` command in your terminal, open it using the Start Menu on Windows or Spotlight Search on macOS as you would any other software. Then click `File > Open File` and use the dialog to navigate to the `/Users/<your-name>/Desktop/projects/git` folder and create a `syllabus.md` file there.

We'll be typing our markdown into this file in the Visual Studio Code window. At any time, you can save your file by hitting <kbd>control</kbd> + <kbd>s</kbd> on Windows or <kbd>⌘</kbd> + <kbd>s</kbd> on macOS. Alternatively, you can click the `File` menu on the top right, then select `Save` from the dropdown menu.

Saving frequently is advised. When we get to the version contol functionality of Git, only changes that are saved will be preserved when a version is created.

---
# Creating Syllabus Content Using Markdown

We'll be using **Markdown** to write a syllabus, and then using **Git** to track any changes we make to it. Markdown allows us to format textual features like headings, emphasis, links, and lists in a plain text file using a streamlined set of notations that humans can interpret without much training. Markdown files usually have a `.md` extension.  

**Markdown** is a markup language for formatting text. Like HTML, you add markers to plain text to style and organize the text of a document.

Whereas you use HTML and CSS with WordPress, you use Markdown to render legible documents on GitHub. Markdown has fewer options for marking text than HTML. It was designed to be easier to write and edit.  

For comparison, you learned to create headers in HTML like this:

```html
<h1>My Syllabus Heading</h1>
```

In Markdown, we insert headings with a single hash mark like this:

```markdown
# My Syllabus Heading
```

A sub-heading (H2) heading uses two hash marks like this:

```markdown
## Readings
```

The lessons of this workshop were originally written in markdown. You can see [here](https://raw.githubusercontent.com/DHRI-Curriculum/git/v2.0/lessons.md) what they look like in their raw, unrendered form.

Compare that with this—the source code for this lesson's web page, written in HTML [here](view-source:http://curriculum.dhinstitutes.org/workshops/git/lessons/).

Markdown is also arguably more sustainable and accessible than formats like `.docx` because of its simplicity and related ability to be read across multiple platforms. Use of Markdown is also supported by document-conversion tools like [Pandoc](https://pandoc.org/) that can change a markdown file to an `.epub` with one command entered into your terminal.

Here are a few more key elements to get you ready to make your own syllabus in Markdown. 

To provide emphasis, place asterisks around some text:

```markdown
*This text will appear italicized.*
**This text will appear bold.**
```

For emphasis, you need to mark where it should start and where it should end, so you need astrisks at the beginning and end of whatever text is being emphasized.

To create a bulleted list, put a hyphen at the beginning of each list item:

```markdown
- Reading one
- Reading two
- Reading three
```

To create a link, put the anchor text (the text you will see) in square brackets and the URL in parentheses, directly following the anchor text in brackets. Don't put a space between them:

```markdown
I teach at [SMU](https://www.smu.edu/).
```

Paragraphs of text are denoted by putting a blank line between them:

```markdown
This is a paragraph in markdown. It's separated from the paragraph below with a blank line. If you know HTML, it's kind of like the <p> tag. That means that there is a little space before and after the paragraph when it is rendered.

This is a second paragraph in markdown, which I'll use to tell you what I like about markdown. I like markdown because it looks pretty good, if minimal, whether you're looking at the rendered or unrendered version. It's like tidy HTML.
```

## Challenge

Use these five elements—headings, emphasis, lists, links, and paragraphs—to create a syllabus. Have a main heading that gives the course title (one `#`), then subheadings for, at least, course info and readings. Use emphasis (`*`) for book titles and try to get a list in there somewhere.

If you want an a more advanced challenge, you can review some additional markdown elements on [this page](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) and add some extra features like images, blockquotes, or horizontal rules.

## Example

You can look at an example syllabus in raw text form [here](https://raw.githubusercontent.com/SouthernMethodistUniversity/dhri/main/sections/data1.md). When it's rendered by GitHub, it looks like [this](https://github.com/SouthernMethodistUniversity/dhri/blob/main/sections/data1.md). When editing the markdown file in Visual Studio Code, it might look like this:

![What your markdown might look like when typed into Visual Studio Code](../sections/images/vscode2.png)

## Tips

1. Visual Studio Code also has a preview feature for your markdown. Hit the preview button on the top right while editing your markdown file:

    ![Button to hit to get a preview in Visual Studio Code](../sections/images/vscode3.png)

    You'll get two side-by-side panels. Your markdown file will be on the left, and your rendered preview will be on the right:

    ![Side by side markdown and preview in Visual Studio Code](../sections/images/vscode4.png)

2. Remember to save your work—regularly!—with <kbd>control</kbd> + <kbd>s</kbd> on Windows or <kbd>⌘</kbd> + <kbd>s</kbd> on macOS.

---

# Staging and Committing Changes

Git's primary function is version control, or to track a project as it exists at particular points in time. Now that we have a file to track—our `syllabus.md`—let's use Git to save the current state of the repository as it exists now.

## A Metaphor for Adding and Committing

In Git, a _commit_ is a snapshot of a repository that is entered into its permanent history. To commit a change to a repository, we take two steps:

1. Adding files to a "staging area," meaning that we intend to commit them.
2. Finalizing the commit.

Staging a file or files is you telling Git, "Hey! Pay attention these files and the changes in them". 

Making a commit is a lot like taking a photo. First, you have to decide who will be in the photo and arrange your friends or family in front of the camera (the staging process). Once everyone is present and ready, you take the picture, entering that moment into the permanent record (the commit process).

Why do you need both steps? Sometimes when you're working on a project you don't want to pay attention to all the files you changed. Perhaps you fixed a bug in some code, but also did some work on your manuscript document. You may want to only commit the changes you made to the code because you still haven't finished your thoughts on the manuscript. You can stage, or `add`, the code file so Git knows to only commit the changes made to that file. Later, you can stage and then commit the manuscript changes on their own once you've finished your thought. 

## Staging Changes with the `add` Command

First, let's see what state Git is currently in. We do that with the `git status` command. It's a good idea to use this command before and after doing anything in a Git repository so you can always be on the same page as the computer.

Make sure you're in your `/home/<your-name>/Desktop/projects/git-practice` directory using the `pwd` command in the terminal. Once you're there, enter `git status` and you should see the following output:

```console
$ git status
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	syllabus.md

nothing added to commit but untracked files present (use "git add" to track)
```

"Nothing added to commit" means that we have initialized our repository, but haven't made any commits yet. _If you're instead getting a message that begins with the word `fatal` when you use `git status`, you may be in the wrong directory or perhaps you haven't run the `git init` command on your directory yet._

Let's follow the recommendation in the status message above and use the `add` command to stage files, making them ready to be committed.

We will go ahead and add `syllabus.md` by writing the following in the terminal:

```console
$ git add syllabus.md
```

You should see no output from the command line, which should be interpreted as a the above command succeeded. It is what we call "succeeding silently." Let's run `git status` again to have a "sanity check"—to make sure that things have changed. You should see output like this:

```
$ git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

	new file:   syllabus.md
```

The `new file:   syllabus.md` should be highlighted in green to show that it's ready for commit.

This is Git telling you, "Ok, I see the file(s) you're talking about."

## Committing Changes

Now that our files have been staged, let's commit them, making them part of the permanent record of the repository. In the terminal, type:

```console
$ git commit -m "Initial commit of syllabus file"
```

The `-m` flag provides that the message following the flag (in quotation marks) along with the commit. The message will tell others—or remind a future version of yourself—what the commit was all about. Try not to type `git commit` without the `-m` flag—there's a note about this below.

After running the command, you should see output like this:

```
[main (root-commit) 8bb8306] Initial commit of syllabus file
  1 file changed, 0 insertions(+), 0 deletions(-)
  create mode 100644 syllabus.md
```

This means you have successfully made your first commit in the repository—congratulations! There are a few things going on in this message. The relevant information for you for now is the second line, which tells you that one file was changed, and there were no insertions or deletions. You have a fresh new file! 

Let's check the state of our repository after the commit by running `git status`:

```
$ git status
On branch main
nothing to commit, working tree clean
```

This means that everything in the repository is successfully committed and up-to-date. If you edit your syllabus file or create a new file in the repository, the message you get with `git status` will instead list files that have uncommitted changes.

Let's run one other command to see the effect our commit has had. Enter this command:

```console
$ git log
```

You should see output similar to this:

```
commit 8bb8306c1392eed52d4407eb16867a49b49a46ac (HEAD -> main)
Author: Your Name <your-email-here@gmail.com>
Date:   Sun May 20 16:03:39 2018 -0400

    Initial commit of syllabus file
```

This is the log of commits, comprising a history of your repository. There's only one commit here now, though. If you don't see a prompt (the `$`) after running `git log`, you may need to press the <kbd>q</kbd> key (just the <kbd>q</kbd> key by itself) to return to the command line.

## Why Do We Need to Use the `-m` Flag?

The `-m` flag is useful for human purposes and technical purposes. For human purposes, the `-m` flag helps you keep track of the changes you're making. Version control is most useful when you can confidently return to a specific version. It can also help you be more structured in your approach to making changes—your notes to self are limited, so to make them clear, you might make commits after specific tasks are completed. If you update readings for the first week of classes or if you add another reading, you will want to make a commit. This can also make it easier to reverse a specific change in the future.

Also, if you type `git commit` by itself, git will open the command line's default text editor to allow you to enter the commit message in a file-like environment. It looks something like this:

![Example of what the vi screen looks like](../sections/images/vi.png)

This unfamiliar screen is the default text editor, `vi`, and it requires some knowledge to use. We don't teach it as part of our sessions, but if you find yourself stuck in this screen, you can try this trick to leave that environment and return to your usual command prompt. Type `:q` and then press <kbd>enter</kbd>. You should be back to the command line with a message saying:

```console
Aborting commit due to empty commit message.
```

If you make a mistake where you include an opening quotation mark but forget a closing one, you might accidentally end up inside a "quote prompt." You will know you're there when your command prompt changes to `quote>`. If this happens, you can just keep writing as much of your commit message as you want, and then end it with the same quotation mark that you opened the commit message with.

Another option is to press <kbd>control</kbd> + <kbd>c</kbd> on your keyboard, which will exit the quote prompt and cancel any commits you were trying to perform.

## Pro-tip for the Command Line: How to exit unknown screens

If you're ever stuck or "trapped" on the command line, try running through these common exit commands to return to the prompt:

- <kbd>control</kbd> + <kbd>c</kbd>
- <kbd>control</kbd> + <kbd>d</kbd>
- `q` followed by <kbd>enter</kbd>
- `:q` followed by <kbd>enter</kbd>

<kbd>control</kbd> + <kbd>c</kbd> attempts to abort the current task and restore user control. <kbd>control</kbd> + <kbd>d</kbd> escapes the current shell environment—if you use it at the normal `$` prompt, it will end the current command line session. `q` is often used as a command (followed by <kbd>enter</kbd>) to escape from specific programs like `less`. `:q` is the command used in `vi` that changes the mode of interaction (`:`), allowing you to enter the `q`, a one-letter command to quit, which must be followed by <kbd>enter</kbd>. Thus, it's a command specific to `vi`.

<sub> [More about Tracking changes](https://swcarpentry.github.io/git-novice/04-changes.html) </sub>


---

# Pushing to GitHub

Now, let's connect the directory you made to GitHub. GitHub is a service that allows us to host files, collaborate, and find the work of others. Once our syllabus is on GitHub, it will be publicly visible.

Go to GitHub in your browser and click the plus sign in the upper right hand corner.

![You can find the plus sign button to add a repo on the top right of github](../sections/images/addrepo.png)

After clicking the plus button, select `New repository` from the dropdown menu.

![The dropdown menu where you select New Repository](../sections/images/createrepo.png)

After clicking `New repository`, you'll have to enter some information, including a name and description for your repository.

![Screen on GitHub where you enter your repository information](../sections/images/createrepo2.png)

- Choose a name, such as `git-practice`.
- Enter a description, such as `Test syllabus for learning Git and GitHub`.
- Keep the `Public — Anyone can see this repository` selector checked.
- Do *not* select `Initialize this repository with a README` since you will be importing an existing repository from your computer.
- Click `Create repository`.

You should end up inside your newly created git-practice repo. It will look like a set of instructions that you might want to use to connect your GitHub repository to a local repository.

The instructions we want consist of three lines underneath the heading `...or push an existing repository from the command line`. The arrow in this screenshot points to where these directions are on the page:

![The commands you need to copy from the new repo page on GitHub](../sections/images/connect-repo.png)

Copy out the first command and paste it in your terminal. It should look something like this:

```console
git remote add origin https://github.com/<username>/<repository-name>.git
```

You'll need the command copied from your new repo, since it will contain the correct URL.

Next, paste the second command. It will look exactly like this:

```console
git branch -M main
```

Finally, paste the third command. It will look exactly like this:

```console
git push -u origin main
```

If you have not used git before, you will need to authenticate with GitHub, and a window will pop up asking you to sign in. Click `Sign in with your browser`:

![The window asking you to sign in to GitHub](../sections/images/github_authenticate.png)

Your browser should open a window asking you to "Authorize Git Credential Manager." Click the green `Authorize GitCredentialManager` button:

![The window asking you to authorize Git Credential Manager](../sections/images/github_credential_manager.png)

You should see a message that authentication succeeded. If so, you may now close the browser window and return to the command line, where you should see output like this:

```console
Total 4 (delta 3), reused 0 (delta 0)
remote: Resolving deltas: 100% (3/3), completed with 3 local objects.
To github.com:<repo-name>/git.git
   916998f..9779fa7  master -> master
```

If you see output like this, go back to your new repository page in the browser and click the `Refresh` button. You should see your `syllabus.md` file on GitHub! Your git credentials are also now stored locally, so you should not need to authorize the credential manager again from that computer.

---

# Cloning and Forking

GitHub was built for sharing and collaborating on projects. A key advantage of the platform is that you can find lots of bits of software that do many different things—such as code for plugins for WordPress or Leaflet. Increasingly, you might find syllabi or open writing projects. If a project is public, you can save a copy of it to your local machine, work on it, save your amendations and share it on your own GitHub account. Like we've already mentioned, GitHub usefully helps track attribution along the way.

Cloning and forking are the basic functions of this capability. Each are first explained below, and followed by an example and activity to further explain.

## Cloning

**Cloning** a repository means making a copy of a repository on GitHub, to download and work on locally—on your local machine. By entering the following code into your terminal, you can clone any public directory on GitHub:

```console
$ git clone <repository-url>
```

When you clone a repository from GitHub, the folder that shows up on your local machine comes built-in with a few things. First, Git is already present, so you don't need to initialize the folder. Also, the connection between your local copy and the online repository is already made, so `git push origin main` will work (no `-u` flag needed).

For practice, let's clone the repository for this workshop about Git and GitHub, which [lives on GitHub](https://southernmethodistuniversity.github.io/git/).

First, let's navigate back to your Desktop folder.

```console
$ cd ~/Desktop
```

Remember that the `~` refers to your home directory. Now let's find the URL we need to clone the lesson.

First, follow [this link to the main page of this lesson on Git and GitHub](https://github.com/SouthernMethodistUniversity/git).

On the main page, there should be a green `Code` button on the right side:

![Image pointing out where the clone or download button is on GitHub](../sections/images/clone.png)

Click the green button and you will see a box with highlighted text under a heading that says `Clone with HTTPS`. If you instead see `Cloning with SSH`, click the small link that says `Use HTTPS`.

Now copy out the text in the box:

![Image showing where the text you need to copy is located](../sections/images/copy-clone-text.png)

Now that you have the text copied, go back to your terminal. Remember, you should be on the `Desktop`. (Hint: Use `pwd` to find out what your current working directory is.)

Once you are in the `Desktop`, type:

```console
$ git clone <copied-url>
```

If the command is successful, the full Git and GitHub workshop's text will be replicated on your local machine. To navigate into the folder, its name is `git` and you can use the `cd` command to access it:

```console
$ cd git
```

Use the `ls` command to take a look at the various files in the lesson folder.

Cloning can be especially useful when you're joining a group project that is hosted on GitHub, and you want your changes to eventually be pushed and shared with that same repository.

But maybe that is not possible or ideal. Maybe you don't want to contribute your changes to someone else's repository. Maybe you want to make a derivative of their folder for yourself, on your GitHub account, and make changes there.

Forking is the step you could take to do this.

## Forking

_Forking_ a repository means making a copy of someone else's repository on GitHub, and saving it to your account on GitHub. This function happens within GitHub, and has nothing to do with what is happening on your local machine. Note that _forking_ will not automatically make the repository appear as a folder on your computer; that's the role of _cloning_.

In order to "fork" the `git` repository into your own GitHub account, follow these steps.

First, go to [the repository for this workshop](https://github.com/SouthernMethodistUniversity/git) on GitHub. Note the `Fork` button in the upper right hand corner. By clicking that button, you can copy, or fork, this repository to your account.

![Image showing where the button to fork a repo is located](../sections/images/fork-button.png)

Doing so would also adjust the attribution information in the upper left hand corner. Your username would replace `SouthernMethodistUniversity`, showing that you are looking at a copy of the repository on your account now. Additionally, it will reference the origin account, in this case, `SouthernMethodistUniversity` below after `forked from`, since this was the origin point of _your_ fork.

![Image showing the changes in attribution that happen when a repo is forked](../sections/images/forking-attrib-chng.png)

Your local machine would come into play when you want to _clone_ that repository so you can work on it locally. This also means that when you push those changes to GitHub, you would be pushing them to a forked repository associated with your own account.

You might use this method if you were going to teach your own Git & GitHub workshop. You could use our repository as a base for getting started, and add more examples or change some language, clarify something further, or create a connection to another workshop you are giving, etc. This allows us to continue to use the workshop as we have it as well. Also, maybe at a later time, we want to merge some of your changes with ours. We can do that too by revisiting your version history.

## Challenge

1. Fork and clone [the repository for this workshop](https://github.com/SouthernMethodistUniversity/git). Note not only _what_ you are doing, but also _where_ you are working when completing these two different tasks.
2. Make changes to the files on your local machine. Remember to save them!
3. Use the 3-step process of stage, commit and push to return the amended files to the repository on GitHub.

## Solution

Rather than write out the solution here, I want to encourage you to go back through the lessons as needed.

You'll know you've completed step one when the project folder (called `git`) shows up on your local machine.

After you've made and saved the changes, you'll know you've completed step three when your changes appear in the project folder on _your_ GitHub account.

*Additional content* 

# Collaborating  
[How can I use version control to collaborate with other people?](https://swcarpentry.github.io/git-novice/08-collab.html)
A BASIC COLLABORATIVE WORKFLOW
* In practice, it is good to be sure that you have an updated version of the repository you are collaborating on, so you should git pull before making our changes. The basic collaborative workflow would be:
- update your local repo with git pull origin main,
- make your changes and stage them with git add,
- commit your changes with git commit -m, and
- upload the changes to GitHub with git push origin main
It is better to make many commits with smaller changes rather than of one commit with massive changes: small commits are easier to read and review.

# Conflicts
[What do I do when my changes conflict with someone else’s?](https://swcarpentry.github.io/git-novice/09-conflict.html)

# Git Cheatsheets
- [Git Cheatsheets for Quick Reference](https://swcarpentry.github.io/git-novice/reference.html#top)
---