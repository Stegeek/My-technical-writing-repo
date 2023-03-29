# Introduction to GitHub

## Table of contents

- [Introduction to GitHub](#introduction-to-github)
  - [Table of contents](#table-of-contents)
  - [Introduction](#introduction)
  - [What is GitHub](#what-is-github)
  - [Why GitHub](#why-github)
  - [Git vs. GitHub](#git-vs-github)
  - [GitHub Desktop vs. GitHub CLI](#github-desktop-vs-github-cli)
  - [Cloning a Git Repository](#cloning-a-git-repository)
    - [How to create an empty repository](#how-to-create-an-empty-repository)
      - [Prerequisites](#prerequisites)
      - [Creating the repository on GitHub](#creating-the-repository-on-github)
    - [How to Clone a git repository](#how-to-clone-a-git-repository)
      - [Prerequisites](#prerequisites-1)
      - [Cloning the repository](#cloning-the-repository)
  - [Committing to a repository](#committing-to-a-repository)
  - [Pull requests](#pull-requests)
    - [Opening a pull request](#opening-a-pull-request)
  - [Conclusion](#conclusion)

## Introduction

GitHub and version control is one of the most salient topics to learn as a developer or software engineer. The scope of which this knowledge is applied is vast and is not constrained to software development only. GitHub can be used for tasks such collaboration with teams, developing complex algorithms, hosting websites among others. GitHub is a tool that can be powerful if it's capabilities are leveraged by the user to produce marvelous results.

## What is GitHub

GitHub is a cloud-based platform that hosts git projects on a remote server. GitHub is used by individuals and teams for version control and collaboration using Git. The GitHub's Graphical User Interface (GUI) is very user-friendly and it allows even novice programmers to leverage the power of Git which could otherwise be very problematic.

GitHub is free for all and anyone can signup and begin hosting their projects without limits. This feature makes GitHub especially popular for open-source projects.

## Why GitHub

GitHub has a myriad of benefits when used by a developer or any GitHub user at any level. Owing to the fact that it hosts git projects on a remote-server, it means that you will have a back up to your project. In case of damage to the local storage, you can still access and retrieve your project files readily in a matter of minutes if not seconds.

Moreover, it is easy to keep track of collaborative and personal projects. Making changes to your project and pushing them to GitHub makes the work of tracking the progress easier. This is also true for collaborative works that involve more than one person. Every person can make their contributions to the project remotely up-to the deployment stage smoothly without conflicting by creating new branches.

GitHub offers one of the best documentations that help beginners to maneuver through its technical areas with ease. The documentations make it easy to solve any problem encountered on the way without requiring a third party to take you through. In addition, GitHub offers a markdown that is used in writing of instructions and explanations about a project (README.md). Markdown is also used by book authors to write their books, and technical writers to write their technical articles.

## Git vs. GitHub

**Git** is an open-source tool that is downloaded on to the computer and is used for version-control. It is used to manage a development's source code history.

**GitHub** is a cloud-based code hosting platform that allows users to save their Git repositories on a remote server. Essentially, it stores code that is pushed to it from computers running the Git tool.
You can learn more about [Git and GitHub here](https://www.theserverside.com/video/Git-vs-GitHub-What-is-the-difference-between-them)

## GitHub Desktop vs. GitHub CLI

**GitHub Desktop** is an application that enables you to communicate with GitHub using a Graphical User Interface (GUI), instead of utilizing the command line or a web browser. The majority of Git operations may be executed from your desktop with visual confirmation using GitHub Desktop. You can read more about how to install and use [GitHub desktop here](https://docs.github.com/en/desktop/installing-and-configuring-github-desktop/overview/getting-started-with-github-desktop)

**GitHub CLI** on the other side is an open-source tool that allows you to interact with the GitHub from the computer's Command Line Interface(CLI). The CLI makes use of the git commands to perform certain tasks. You can find out more about the GitHub CLI and how to install it [here](https://docs.github.com/en/github-cli/github-cli/about-github-cli).
Some of the commands that are used in the GitHub CLI can be found at the [GitHub documentation](https://docs.github.com/en/get-started/using-git/about-git#about-version-control-and-git).

## Cloning a Git Repository

### How to create an empty repository

#### Prerequisites

In this section, it is assumed that you have already created a GitHub account and your first task will be to create a repository otherwise known as a repo. If you have not created an account, you can create one from [github.com](https://github.com/).
You will use the web-version of GitHub for this activity.

#### Creating the repository on GitHub

1. Click the **_+_** on the top right corner of your GitHub home page and it will show a dropdown with options.
   ![New Repository button](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/u3cd70da9zz1tg37ss82.jpeg)

2. You will use the **New repository** option that is shown on the dropdown. Click on that option which will take you to a new page.

3. In the next step, you are required to give your repository a name. You can write your own repository name or use the one suggested for you.

4. Write a short description of your repository. This step is optional but preferable.

![Repository description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/fdyib7ooo0vny7y6j94n.jpg)

5. You are required to choose whether your repository will be **public** or **private**. For this tutorial we will set the repository to be public and everyone in the internet can see it.

You can add a **README** file which is used to talk briefly about your project. The README file also gives instructions to the people interacting with the project on how to use the project. At this stage you will not be required to add a README file since you will be creating an empty repository. Other files you can add to your repository include:

- Git ignore file. You can find out more about a git ignore file [here](https://git-scm.com/docs/gitignore#:~:text=A%20gitignore%20file%20specifies%20intentionally,gitignore%20file%20specifies%20a%20pattern)

- License.

You will not require the above files for now and we will leave them out.

![Additional files](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/38i140nabm8nh9genomm.jpg)

6. Click on the **`Create repository`** button at the bottom to finish creating your repository.

![Create Repository button](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/ijgv7ik4ihky13yvlwo0.jpg)

After creating you repository, you will be redirected to another page with the link to your repository. You will need this link when you will be cloning your repository to your local machine for changes.

On that page, you will see other alternative ways of **creating a repository from the command line, pushing an existing repository from the command line** and **importing code from another repository**.

7. Copy the link to the repository by clicking on the clipboard symbols on the right side of the link.

![Copy the repository link](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/pcfusyku5w5izw7xhqak.jpg)

Now you are ready for the next step, cloning.

### How to Clone a git repository

**Cloning** is the act of copying a repository from [GitHub.com](https://github.com) to your local machine. Your clone will contain all the project files (if any), history and branches.

You can also contribute to repositories belonging to other people or already in existence. All you will need is the link to the repository.

- Select the repository you want to clone and click
  on the green button labelled **`code`** and it will show a
  dropdown.
- Choose the `HTTPS` option and copy the link to the
  repository by clicking on the clipboard symbol on the far-right
  of the link.

![Repository link](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/sugmxj4bek1gln65an8u.jpg)

#### Prerequisites

You are supposed to have installed **git** into your computer for this section. If you have not installed it yet, you can learn how to install git which will be compatible with your machine from [Git Guides](https://github.com/git-guides/install-git).

#### Cloning the repository

In this article I will be using the windows Git Bash, but Git can be downloaded to any Operating system including macOS and Linux/Unix distros [See here](https://git-scm.com/downloads).

Search for **git bash** in the search bar found on the bottom left corner of your windows machine and click on `open`.

![Git Bash](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/mwolx4n9wg9mzxv7vg84.jpg)

Write the commands below to clone the repository.

```INI
# download a repository on GitHub to our machine
# Replace `owner/repo` with the owner and name of the repository to clone
  git clone https://github.com/owner/repo.git

# It will look like this for the repository that we created
  git clone https://github.com/<your username>/github-
  introduction.git

```

## Committing to a repository

According to Wikipedia, a **commit** is an operation which sends the latest changes of the source code to the repository, making these changes part of the head revision of the repository, in version control systems.

We use git commands to stage the changes made to the repository and finally push them to GitHub. The commands that are used in committing the repository include:

- `git add` - stages a change.

- `git commit` - completes the change-tracking procedure by adding the snapshot to the project history. In essence, committing works like taking a picture. With `git commit`, anything that has been staged with `git add` will be added to the snapshot.

- `git push` - Updates a branch's remote repository with any commits made locally.

To learn more about the git commands, refer to [GitHub documentation](https://docs.github.com/en/get-started/using-git/about-git#about-version-control-and-git)

```INI

# Change into the `github-introduction` directory
  cd github-introduction

# Make changes, for example, create a `README.md` and `file1.md` using the text editor
  touch README.md
  touch file1.md

# Check to confirm the files you have created using the `ls` command
  ls

# stage the changed files
  git add .

# take a snapshot of the staging area (anything that's been added)
  git commit -m "My first commit"

# push changes to GitHub
  git push --set-upstream origin main

```

## Pull requests

A **Pull Request** is a "message" that lets you inform other contributors of the changes that you have pushed to a branch in a repository on GitHub.

You contribute to other people's projects by creating a new `branch`, which essentially gives you a copy of what is there in the `main` branch. You can make your changes in the new branch and commit the changes to GitHub before opening a pull request.

A `pull request` proposes your changes to someone, asking the person to review, pull in your contributions and merge them into their branch. It shows the differences of the contents from both branches.

### Opening a pull request

```INI
# Pull the repository that you pushed to GitHub so that you can be update your local repository
 git pull

# Create a new branch and switch to the new branch
 git checkout -b new-branch

# Make some changes to the files that you created.
# Write something inside the file.
# Press `CTRL` + D to terminate the command
  cat > README.md

# stage the changes made to the files
git add .

# take a snapshot of the staging area (anything that's been added)
git commit -m "Modified README.md file"

# push changes to GitHub
git push --set-upstream origin new-branch
```

You will now have changes in a branch off the main branch. You can now open a pull request.

1. Click on the **Pull requests** tab of your `github- 
introduction` repository.

![Pull request tab](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/xiw19tx3brmml5mg7afn.jpeg)

2. Click **New pull request** button.

![New Pull Request button](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/n9kpkc3t7kxi8jsb4fs6.jpeg)

3. In the Comparisons box, select the branch you made changes to, `new-branch`, to compare with main branch (the original).

![Comparisons box](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/a2v8mm52olepw1cvmcid.jpeg)

4. Confirm the changes in the **diffs** on the comparing changes page and make sure they are the changes that you want to submit.

5. Click **Create pull request**.

![Comparing changes](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/oqww5u1tw1kjgdoh37uy.jpeg)

6. Give your pull request a title and a brief description of changes made.

7. Click **Create pull request**.

![Finish up creating the pull request](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/12xccdgxpqlfzpdn4scl.jpeg)

Congratulations!🎉 You have created a new pull request ready for review and merging of your branch. You can learn more about Git and GitHub from the [GitHub docs.](https://github.com/skills/introduction-to-github)

## Conclusion

By using Git and GitHub, your production is boosted and you can focus the time you spent thinking about your project history to other projects. GitHub, and specifically, pull requests are the heart of collaboration. You can contribute to projects from anywhere around the globe and be sure of no data loss. This article will help you get started with version control using Git.
