# How to use GitHub
**Hands on workshop, online**
- In this 60 minute workshop, participants will be introduced to GitHub and how to access online repositories. 
- based on GitHub Docs [Hello World exercise](https://docs.github.com/en/get-started/quickstart/hello-world)
  - **GitHub Skills**
    - [Learn how to use GitHub with interactive courses designed for beginners and experts](https://skills.github.com/)

**Github** (required)  
- **[Create a GitHub account](https://github.com/join) (required)**
- You need to have a GitHub account for the purposes of this workshop. It is free to sign up [via this link.](https://github.com/join)
- For SMU affiliates (students, faculty,staff): If you already have an account, you *do not need to create another account.* In the settings section of your personal account, **you can add additional emails, such as your SMU email.** 

# What are Git & GitHub ?
- Go through [Introduction to Git & Github.](https://southernmethodistuniversity.github.io/git/whatgitandgithub.html)

- **In this workshop we will:** 
- Create and use a repository
- Start and manage a new branch
- Make changes to a file and push them to GitHub as commits
- Open and merge a pull request
  - We will do this on the [Github platform](https://github.com/). **We will *not be* installing git or using the command line in this workshop.**
  - We will **either** fork a repo OR create a repo

________________________
# Contributing to a Github Repo

There are many ways to contribute to a GitHub repo, from creating issues that suggest improvements to specific files to creating entirely new sessions. We will discuss various modes of interaction with a repo, including *forking* a repository to your account, *creating issues* and *pull requests.*
______________
## Creating Issues

A critical and relatively accessible way to contribute back to a repo is to create an issue on GitHub. While reading a repo on GitHub, you may encounter inconsistencies, typos, sections that need clarification, or typographical errors. When this happens, you can open an issue to let them know about the problem or potential improvement.

To open an issue, you must be in a GitHub repository. In the menu bar at the top center of the page, click the `Issues` tab.

![Image showing that the Issues tab is in the center menu bar above the files in the GitHub repository](..images/issues_tab.png).

After clicking the issues tab, you will see a screen with the currently open issues, if any. To create a new issue, click the large green button on the right of the page.

![Image showing where the Create New Issue button is in the Issues tab on GitHub](images/new_issue.png)

On the New Issue page, there is only one required field—the issue title. However, consider leaving a detailed explanation of the issue, including which file you encountered it, if relevant. You can use markdown formatting in the body of your issue.

To complete your issue, click the green button labelled `Submit New Issue`.

![Image showing where the submit new issue button is. In the issue body box, the message reads "In loop.md, I noticed that the index of the example is flowers[1], which is not "rose" as the output indicates. Looks like it should be 0."](/images/finish_new_issue.png).

 ________ 
# *Fork* a repo
* [About forks](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/about-forks)
* **We wll be forking the [Introduction to GitHub repo.](https://github.com/skills/introduction-to-github)**

## Forking
By default, you will not have access to directly modify repos. In the world of free and open source software, this is common—usually, only the creator of a repository and certain core contributors can add and modify files in a repository. However, this doesn't mean that you cannot modify the repo and make it your own.

If you wish to create your own version of the repo for your own use , the first step is to **fork** the relevant repository. That means to make a copy of it under your own account on GitHub, one in which you have access to modify files. Once you have forked a repository, you can create a new lesson based on it. Because the (majority of ) curriculum is under a Creative Commons license, you may use any module as the basis for a new lesson and share freely, as long as you provide attribution and share under the same license.

To fork a repository to your account, click the `Fork` button at the top right of any repository on GitHub.

![Image showing where fork button is on GitHub](fork.png)

After clicking the fork button, if you're a member of an organization on GitHub, you may see a screen asking you to which account you wish to fork the repository. Choose your personal account. If you are not a member of an organization, you will not see this screen.

Once you have clicked `Fork` and (possibly) chosen an account or organization, you will see a screen showing you that the fork is in progress:

![Image showing the fork in progress](currently-forking.png)

Once the fork is complete, you will be directed to a screen showing the repository in your own account.

![Image showing the forked repository in your own account](after-forking.png)


OR 
______________________

*start from scratch* 
# *Create* a repo
## [Create and use a repository](https://docs.github.com/en/get-started/quickstart/hello-world#creating-a-repository)
- Define: Repository, README, Markdown
  - In the upper-right corner of any page, select, then click New repository.
  - In the "Repository name" box, type hello-world.
  - In the "Description" box, type a short description.
  - Select whether your repository will be Public or Private.
  - Select Add a README file.
    - README written in [Markdown](https://www.markdownguide.org/cheat-sheet/) 
  - Click Create repository.



*Now that we have a repo on our account (either created new or forked), we will make some changes*

# *Create* a branch
## [Start and manage a new branch](https://docs.github.com/en/get-started/quickstart/hello-world#creating-a-branch)
- Define: main, branch
 - Branching lets you have different versions of a repository at one time.
- Click the Code tab of your hello-world repository.
- Above the file list, click the dropdown menu that says main.
- Type a branch name, readme-edits, into the text box.
- Click Create branch: readme-edits from main.
  - Now you have two branches, main and readme-edits. Right now, they look exactly the same. Next you'll add changes to the new branch.
    - [Learn about Git branching using an interactive tool](https://learngitbranching.js.org/)

# Commits
## [Make changes to a file and push them to GitHub as commits](https://docs.github.com/en/get-started/quickstart/hello-world#making-and-committing-changes)
- Define: changes aka commits, commit messages.  
  - VERSION CONTROL: Each commit has an associated commit message, which is a description explaining why a particular change was made
- Under the readme-edits branch you created, click the README.md file.
- To edit the file, click the pen icon.
- In the editor, write a bit about yourself. Try using different [Markdown elements](https://www.markdownguide.org/cheat-sheet/).
- Click Commit changes....
- In the "Commit changes" box, write a commit message that describes your changes.
- Click Commit changes.
  - *These changes will be made only to the README file on your readme-edits branch, so now this branch contains content that's different from main.*

## [Open and merge a pull request](https://docs.github.com/en/get-started/quickstart/hello-world#opening-a-pull-request)
- Define: pull request
 - Pull requests show diffs, or differences, of the content from both branches.
- Click the Pull requests tab of your hello-world repository.
- Click New pull request
- In the Example Comparisons box, select the branch you made, readme-edits, to compare with main (the original).
- Look over your changes in the diffs on the Compare page, make sure they're what you want to submit.
- Click Create pull request.
- Give your pull request a title and write a brief description of your changes. You can include emojis and drag and drop images and gifs.
  - Optionally, to the right of your title and description, click the  next to Reviewers, Assignees, Labels, Projects, or Milestone to add any of these options to your pull request. You do not need to add any yet, but these options offer different ways to collaborate using pull requests. For more information, see ["About pull requests."](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests)
- Click Create pull request.
  - Your collaborators can now review your edits and make suggestions.
    - [More About pull requests](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests)

## [Merging your pull request](https://docs.github.com/en/get-started/quickstart/hello-world#merging-your-pull-request)
- Define: merge, conflicts 
- At the bottom of the pull request, click Merge pull request to merge the changes into main.
- Click Confirm merge. You will receive a message that the request was successfully merged and the request was closed.
- Click Delete branch. 
 - Now that your pull request is merged and your changes are on main, you can safely delete the readme-edits branch. 
 - If you want to make more changes to your project, you can always create a new branch and repeat this process.


