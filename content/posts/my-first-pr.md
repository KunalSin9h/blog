---
title: "Make your first Pull-Request on Github"
date: 2022-08-13T16:22:25+05:30
weight: 1
# aliases: ["/first"]
tags: ["git", "github", "open-source"]
author: "Kunal Singh"
# author: ["Me", "You"] # multiple authors
showToc: true
TocOpen: false
draft: false
hidemeta: false
comments: false
description: "A step-by-step guide to getting started with open source development."
# canonicalURL: "https://canonical.url/to/page"
disableShare: false
disableHLJS: false
hideSummary: false
searchHidden: true
ShowReadingTime: true
ShowBreadCrumbs: true
ShowPostNavLinks: true
ShowWordCount: false
ShowRssButtonInSectionTermList: false
UseHugoToc: true

cover:
    image: "https://kunalsin9h.dev/store/images/banner.png" # image path/url
    alt: "Git and Github logo banner" # alt text
    caption: "<text>" # display caption under cover
    relative: false # when using page bundles set this to true
    hidden: false # only hide on current single page
editPost:
    URL: "https://github.com/KunalSin9h/blog/content"
    Text: "Suggest Changes" # edit text
    appendFilePath: true # to append file path to Edit link
---

> In this blog, we'll look at how you can make our first open source contribution on Github. We will learn how to make changes and publish using a real GitHub repository.


[![First-Pull-Request/my-first-pr - GitHub](https://gh-card.dev/repos/First-Pull-Request/my-first-pr.svg?fullname=)](https://github.com/First-Pull-Request/my-first-pr)


We will use the above repository as the sample and at the end, we can push the changes to this. I hope you already have a Github account and Git installed and are ready to proceed.

## 1. Fork the repository

The first thing for making any changes to an open-source project is to fork it. Forking means making the exact copy of the project for us. Now, this copy is ours, so we can make any changes to it.

For this click to the **Fork** button the Github.


![Fork The Project Image](https://kunalsin9h.dev/store/images/fork.png)

After clicking on **Fork** you will see something like this.

![Create Project](https://kunalsin9h.dev/store/images/making-fork.png)

Click on **Create fork** and now you have your own copy of this repository. We can now do some changes, to this.


## 2. Clone the repository

At this point you will see something like this.

![Created Project](https://kunalsin9h.dev/store/images/toclone.png)

Now copy the projects url by clicking on **Code** and then copying the link.

![Clone Project](https://kunalsin9h.dev/store/images/clone.png)

You have copied the link now open the *Terminal* or *Git bash* and type this to clone the repository to the local computer. So that we can use our favorite code editor to make changes.

```bash
git clone https://github.com/First-Pull-Request/my-first-pr.git
```

Congratulations, you have successfully cloned this repository. Now we are ready to make changes.


## 3. Making changes

Now we can start making changes to do so open this repository in your favorite code editor.
The First thing we do is Create a new **Branch**. Creating a new branch for every new change is the best practice. To do so type this in *Terminal* or *Git bash*.

```bash
git checkout -b new-change-branch
```

here **checkout** means to switch to a branch and **-b** means to create a new branch. Then open **hello.txt** file in **contribute** folder.

Make a change by adding your name just like shown in this template.

Save the **hello.txt** file, now stage and commit the changes.

![Stage and Commit](https://kunalsin9h.dev/store/images/commit.png)


## 4. Push changes

In above section we have successfully commited the changes, now it's time to push to origin. To push to origin with new branch we do.

> **origin** is a shorthand name for the remote repository that a project was originally cloned from.

```bash
git push origin new-change-branch
```

this will update the origin repository with changes in the new branch.


## 5. Pull Request

Now the time has arrived to make our first pull request. Go to the repository page on Github you will see something like this

![Pull request](https://kunalsin9h.dev/store/images/pr.png)

Click on **Compare & pull request**, you will be rediredted to this page where it aks for title and comment.

![title-and-comment on pull request](https://kunalsin9h.dev/store/images/dopr.png)

Click on **Create pull request**, now you opened a pull request, it will be merged by authors/team members.

![pull-request](https://kunalsin9h.dev/store/images/opened.png)

`Wait for the response and have fun.`