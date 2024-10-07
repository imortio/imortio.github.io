+++
title = "Git Gud with Git"
date = "2024-10-06T13:09:21Z"
author = "arxnoire"
authorTwitter = "" #do not include @
cover = "cover.png"
tags = ["introduction", "git", "versioncontrolsystem"]
keywords = ["Git", "Version Control System", "Github"]
description = "Let’s learn about Git, the foundational tool that empowers you to manage code changes effortlessly."
showFullContent = false
summary = "A newbie introduction to Git"
readingTime = true
hideComments = true
+++

## Git, a tool to ease your way to be _git gud_ at version control.

Git, it has been a popular thing among developers for some years, yet so many people still didnt know what is it exactly. You may have come upon it while scrolling through social media, or maybe forums like stackoverflow, where individuals quite oftenly mention it in their comments or posts like _"Heyya check out this!, my latest Github project, you can use git to fetch and modify it yourself"_ or something else like that which mention Git or Github.

Perhaps you're thinking, "What makes Git so special?", "Why are so many people raving about it?", or "What's in it for me if I start using it?" Don't worry, you aren't alone!, because i had the same question when i first encountered Git too :)

In this article, we'll explain what Git is, why it's become such an important tool in the coding industry, but how about Github?, it can be learned later, as for Git and Github is pretty related each other, so by the time youre learning Git you will be get used to Github too, and trust me, it can make your life as a programmer be much simpler.

![Git Logo](git.png)

So, Git is a distributed version control system, which allow you to monitor changes to your code over time, eventually making it simple to see what has been changed and by whom ( even if only changed by yourself it may be confusing tho if you have a bunch of revisions ). It's ideal for collaborating with other developers since it allows everyone to work on the same project without disagreement. Git also makes you able to maintain many versions of your project, allowing you to try out new ideas without messing with the main project, return to prior versions, or work on numerous features at the same time without losing progress.

# Why i must use it? im fine with multiple different file that represent different versions

Yeah you may say that when you have like less than 15 different file revision, but how about if you want to make a quick rollback?, how about if you just mess up with your other files? or just simply cant remember which one is the right file when its come to rollback?, this is where Git do its job, Git simply said serve as your 'checkpoint' tool (in git we call it commits), which allow you to make 'quicksave' without duplicating the file or making you directory become mess, you also able to give label to your commits so you may simply take a quick glance at the commit history and know which one that you want to use.

Imagine like you are having a task to make movie script, but its keep getting revised everytime you show them, you may change some or many things in each revision, but there is a probability that you may use some scene from older scenario to adds up to your newer revision, so you save the files with different name, like **scene.txt**, then get revised so you renamed to **scene_old.txt**, its get revised again so you need to rename it to **scene_old_1.txt**, then again and again, until you have like 20 different files, such a painfull things aint it?

Your files will eventualy looks like this
![duplicated file](example.png)

So much different files, although they do serve the same purpose, so why would you want this mess? when you can just make one file with many different versions using git, then your directory will look much neat and organized, like this:
![after using git](example_2.png)

"But where is the different versions of the file? i dont see it anywhere else in my directory?" they are saved on Git, and you can check your revisions on Git, here is how to do it.
```bash
git log
```
And you will see the results like this:
![git log result](gitlog.png)

As you can see there is 3 different versions but the main file is still one file, along with the commit messages that is helpful to keep your changes on track with some related keywords without the need to look into each file manually.

That is just a bit about Git, there is much more Git capabilities like comparing two versions and see what changes between them, also makes much different version of file at the same time while keeping the main file intact, and much more other powerful things, but no rush, we will learn about them later step by step, lets be sure to have well understanding about one topic first before move to other, it would make you easier to learn about anything else furthermore.

Now, have you see a bit of the usefulness of git?, exactly, so here is the conclusion:
- **What is Git?**:
  Git is a distributed version control system that helps you track changes in your project, manage different versions, and collaborate efficiently with others.

  - **What is Version Control System?**:
  Version Control System, also know as VCS, is essential for managing code changes efficiently. It tracks changes, allows easy rollback, and supports collaboration without file clutter.

- **Why use Git?**:
  It organizes your project, saves you from having multiple duplicate files, and allows you to roll back changes easily without cluttering your directory.

- **What exactly is Commit and Track Changes?**:
  A commit is a checkpoint, or snapshot of your project's state at a specific time, including a unique identifier and a description of changes. Tracking changes allows you to monitor modifications, identifying who changes them and when, it helps to maintaining a project history.

So in short, Git is an essential tool for developers, and the sooner you familiarize yourself with it, the more neat and efficient your coding journey will become. Stay tuned for the next article where we dive into setting up Git on your computer. see ya! :D

> **Note:** This article is not yet perfect, could you provide suggestions for changes or feedback so I can improve it later. Feel free to contact me anytime if you'd like here: [Email Me](mailto:nixvoid@proton.me) or [Chat Me on Whatsapp](https://wa.me/+6282284528116)
