# Guide for Git in this Game Jam 

The plan: use this GitHub repo to store the Unreal project. I have set up various things already (e.g., files to ignore). I think we should use git lfs, even if we don't end up having any large (100mb) files, because it may be too disruptive if we need to set it up half-way through the jam. 

This doc will tell you how to set up your own stuff, and how to actually use git during this game jam.

*Note*: In addition to the instructions below, someone will need to create the Unreal project and push it to this repo!

## Setup

There are three important steps you need to follow before you can use this repo!

1. Install git
2. Set up how you will use git
3. ~~Enable 'One File Per Actor' in Unreal~~ (not needed actually)

### Install git

You can follow [this guide](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git). Scroll down a bit for Windows instructions. 

### Set up how you will use git

#### Github account

The first thing you need is a github account! Then you should tell me (David) your username so I can add you as a collaborator (so you can make changes to the project files).

#### Git client

A git client is just a way to use git. There are many options for this, and we don't all need to do it the same way. But I am recommending using **Github Desktop**. It just seems like the best way from my research! You can install it [here](https://desktop.github.com/download/). (If you are not use GitHub Desktop, make sure you have [git LFS installed](https://docs.github.com/en/repositories/working-with-files/managing-large-files/installing-git-large-file-storage))

An **important setup** step is cloning (i.e., downloading) this repo, which you can do from within Github Desktop. 


## Actually using git

There are some complicated things about git. But all you really need to know is how to pull changes from this repo, create a branch where you can make your own changes to the project, and then push those changes into this repo so everyone else can access them. 

I would recommend [this video](https://www.youtube.com/watch?v=7X0R-sa4J5Q) to get a good background understanding of using Github Desktop with Unreal. It also shows how to integrate git with the build in revision control. However, the context is slightly different, as I have already made the GitHub repo. 

This is the workflow I am suggesting:

1. Make a branch for yourself
2. Do some work on the project
3. Whenever you do something significant, push your work to this repo
    1. *Commit* your changes to your branch
    2. *Checkout* (switch to) the main branch
    3. *Pull*/*fetch* any new changes to the main branch
    4. *Merge* you branch into the main branch
    5. *Push* your changes to the main branch onto GitHub
4. Repeat steps 2-3

Step 3 is a little bit complicated, so [here is a video](https://www.youtube.com/watch?v=Btu0SuwPmz0) of someone merging a branch into the main branch with Github Desktop. He misses step 3.3, which you can do by clicking the 'Fetch origin' button at the top after switching to the main branch.

