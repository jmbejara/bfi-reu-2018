bfi-reu-2018
============

Part of becoming good at developing code is learning to use the proper tools. Here, we're going to talk about a few important general purpose software development tools. We'll then work through some examples related specifically to economics.

# Markdown

First we will briefly talk about Markdown. Markdown is used in R Markdown and R Notebook files. We will connect Markdown to our discussion on Git and GitHub.

  - Vanilla markdown in R Studio
    - Here is an overview of Markdown: https://rmarkdown.rstudio.com/authoring_basics.html
    - Go over [example markdown file](./markdown/example.md) in R Studio
  - GitHub Markdown
    - Here is a cheatsheet for ["GitHub Markdown"](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

# Git and GitHub

Here we will take some time to learn the basics of version control with Git and GitHub. The Git client and GUI that we will is GitKraken. GitHub is the platform that we will use to host our Git repositories.

* What is version control and why should I use it?
  - A better system for organizing revisions of code and documents
  - Jump back and forth throughout the history of you project
  - Jump between different branches of your project (non-linear history).
  - Make collaboration easier (view and annotate diffs, separate repos, comment on and approve pull requests)
  - Go over main points in this [Git basics tutorial](https://git-scm.com/book/en/v2/Getting-Started-Git-Basics)

* Example 1 (follow along):
  - Create new repo on GitHub. Make sure it is a public repo. Personalize the name of the repo (e.g., example1-jeremy).
  - Use the in-browser editor to edit the main README.md
  - Upload example Markdown file. Don't include the image. This will be a purposefully included bug.
  - Create a bug report in the issue tracker. Include a screenshot and a code chunk in the issue description. Also, reference the commit in which the bug was introduced. Add an `@` mention of someone (me?) in the issue description. Assign the bug to yourself.


* Git Repositories
    - What is a repository in Git? (just a folder)
    - What is the difference between a local repository and a remote repository?
    - Cloning and tracking a repository

* GitKraken
  - Clone the repo from Example 1
  - Quick overview of [GitKraken interface](https://support.gitkraken.com/start-here/interface)
  - Show how new changes appear when I edit a file or create a new file
  - Make a random change, commit it, and push the changes.
  - Discuss branching. Create a new branch. Make a change. Commit. Merge commit into master. Do the same with rebase.
  - Create a branch representing an experiment. Push the branch to the remote but don't commit it. View the different branches on GitHub.

* **Exercise 1:**
  - Fix the issue from before. Use GitKraken to make the commit and push the changes. Make the changes in a separate branch first and then merge the changes into master.
  - Reorganize the files in the repo. Put the markdown example file, along with the linked image, in its own folder. Commit and push these changes.

* Forking a Repository (watch me do this fist, then you try)
  - Make a fork of a neighbor's repository. Add a new file called `collaborator.md`. This should contain the line `Collaborators: [your name].` Commit the changes and push them to your fork. 
  - Open a pull request upstream. Your neighbor should accept and merge the pull request.

# FRED and Quandl

In this portion, we will discuss the data sources available on FRED and those available on Quandl.

  - Find a measure of inflation on FRED. Download the graph as an image. (FPCPITOTLZGUSA)
  - Do the same for real GDP (pct change). (A191RL1Q225SBEA)
  - Use the online tools (GEO-FRED) to create a Choropleth map of unemployment rates by county in the US.


# Python Basics and Optimization

  - Go over Python basics in Colab
  - See the optimization folder.