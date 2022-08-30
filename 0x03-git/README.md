[Optional] Vagrant
==================

DevOpsVirtual machine

-   By: Julien Barbier
-   Weight: 1
-   Project will start Aug 29, 2022 6:00 AM, must end by Sep 3, 2022 6:00 AM
-   was released at Aug 29, 2022 6:00 AM
-   An auto review will be launched at the deadline

### Concepts

*For this project, we expect you to look at this concept:*

-   [Using Vagrant on your personal computer](https://alx-intranet.hbtn.io/concepts/81)

Vagrant - or - how to code in your local computer
-------------------------------------------------

Sandboxes are great, but you can also do your ALX assessments on your local computer - having a virtual machine (VM) is the perfect tool for that.

Let's dig into **Vagrant** today!

Also:

-   This project is **100% optional**
-   This project **can't be done in Sandboxes** - it can be done only in your local computer.

Resources
---------

**Read or watch**:

-   [Virtual machine](https://alx-intranet.hbtn.io/rltoken/eoV8V_5fgzW_UhJ3PtVyWw "Virtual machine")
-   [man uname](https://alx-intranet.hbtn.io/rltoken/Z4MowYniH5YJoZo4jZgIBw "man uname")

Learning Objectives
-------------------

At the end of this project, you are expected to be able to [explain to anyone](https://alx-intranet.hbtn.io/rltoken/g5OVhHRsT0jjsvUI1Y8jgw "explain to anyone"), **without the help of Google**:

### General

-   What is a virtual machine
-   What is Vagrant
-   Who wrote Vagrant
-   What is Ubuntu
-   What does "Ubuntu" mean
-   How to use VMs with Vagrant
-   What does the command `uname` do

### Copyright - Plagiarism

-   You are tasked to come up with solutions for the tasks below yourself to meet with the above learning objectives.
-   You will not be able to meet the objectives of this or any following project by copying and pasting someone else's work.
-   You are not allowed to publish any content of this project.
-   Any form of plagiarism is strictly forbidden and will result in removal from the program.

Requirements
------------

### General

-   A `README.md` file at the root of the repo, containing a description of the repository
-   A `README.md` file, at the root of the folder of *this* project (i.e. `0x00-vagrant`), describing what this project is about

More Info
---------

### Install `git`

If `git` is not already installed on your terminal:

```
$ sudo apt-get update
$ sudo apt-get upgrade
$ sudo apt-get install git

```

### Basic usage

At the end of this project you should be able to reproduce and understand these command lines:

```
$ git clone <repo>
$ touch test
$ git add test
$ git commit -m "Initial commit"
$ git push origin main

```

### Warning

This project **can't be done in Sandboxes** - it can be done only in your local computer. Please refer to our concept pages for your operating system.

### Quiz questions

**Great!** You've completed the quiz successfully! Keep going! (Show quiz)

Tasks
-----

### 0\. Create and setup your Git and GitHub account

#advanced

You will need Git for this project, you might have to [install it](https://alx-intranet.hbtn.io/rltoken/7kPsched1VMPOY2bdvZvGQ "install it") on your computer if it's not done yet.

-   Configure your basic info (name, email) on your local machine -- they will be part of your commits. [Tips](https://alx-intranet.hbtn.io/rltoken/oAAqmPJ1ftZZhUjaw7FvjA "Tips")

On [GitHub.com](https://alx-intranet.hbtn.io/rltoken/4vp5Qze3WATHKtytzT2_UA "GitHub.com"):

-   Using the graphic interface on the website, create the repository (if it's not done yet)
    -   Description: `This is my first repository as a full-stack engineer`
    -   Public repo: `zero_day`
    -   No `README`, `.gitignore`, or license

On your computer, open a terminal and do the following:

-   Navigate to your home directory. [Tips](https://alx-intranet.hbtn.io/rltoken/YeOwsN-vhfSCbNjgE01Gag "Tips")
-   Create a directory `zero_day`. [Tips](https://alx-intranet.hbtn.io/rltoken/hWrqqlilEv8L6yqpyt1TTA "Tips")
-   Navigate to this new directory. [Tips](https://alx-intranet.hbtn.io/rltoken/za58mq537U6U775osQ8bfQ "Tips")
-   Initialize git and add the remote origin
-   Create a file `README.md` with Emacs (or other command line editors) and write a small [Markdown](https://alx-intranet.hbtn.io/rltoken/VV79mKOEf5mXVbKpH4i63Q "Markdown") text to present this project. **This file is mandatory in projects**
-   Add this new file to git, commit the change with this message "My first commit" and push to the remote server / origin (Note: You will probably need to set your login/password to push to the remote server)

Good job!

You pushed your first file in your **first repository** of the **first task** of your **first School project**.

**Repo:**

-   GitHub repository: `zero_day`
-   File: `README.md`

 Done? Help Check your code

### 1\. Hello Ubuntu

#advanced

Inside the `zero_day` repo, create a new directory called `0x00-vagrant`. Add a `README.md` file to this directory.

`ssh` into your Ubuntu VM. What does the command `uname` print when you run it without any option?

Type your answer into a file in the `0x00-vagrant` directory and push it to GitHub. Name your file accordingly as shown below.

**Repo:**

-   GitHub repository: `zero_day`
-   Directory: `0x00-vagrant`
-   File: `0-hello_ubuntu`

 Done? Help Check your code

Copyright © 2022 ALX, All rights reserved.,Toggle navigation[](https://alx-intranet.hbtn.io/)

0x03. Git
=========

GitCode versioningGithub

-   By: Guillaume
-   Weight: 1
-   Project will start Aug 30, 2022 6:00 AM, must end by Aug 31, 2022 6:00 AM
-   was released at Aug 30, 2022 6:00 AM
-   An auto review will be launched at the deadline

### Concepts

*For this project, we expect you to look at these concepts:*

-   [Right-engineering, right-documenting](https://alx-intranet.hbtn.io/concepts/6)
-   [Source code management](https://alx-intranet.hbtn.io/concepts/22)
-   [Git and Github cheat sheet - Everything in less than 30 seconds](https://alx-intranet.hbtn.io/concepts/57)

Resources
---------

**Read or watch:**

-   [Resources to learn Git](https://alx-intranet.hbtn.io/rltoken/YtcpriOT-x-WiyScwLpn4Q "Resources to learn Git")
-   [About READMEs](https://alx-intranet.hbtn.io/rltoken/R7MeJ8alpK3JoVF8w24wiQ "About READMEs")
-   [How to write a Git commit message](https://alx-intranet.hbtn.io/rltoken/FYsjjR-97Hk4NJtgqzWdtQ "How to write a Git commit message")

**Resources for advanced tasks** (Read only after finishing the mandatory tasks):

-   [Learning branching](https://alx-intranet.hbtn.io/rltoken/tN8ZJ0yWubOP6jdciqtrFw "Learning branching")
-   [Effective pull requests and other good practices for teams using GitHub](https://alx-intranet.hbtn.io/rltoken/mjpQ9OCU0Dz-DFxZjASEJg "Effective pull requests and other good practices for teams using GitHub")

Learning Objectives
-------------------

At the end of this project, you are expected to be able to [explain to anyone](https://alx-intranet.hbtn.io/rltoken/jj0uPL9hiKF10KCH4u620A "explain to anyone"), **without the help of Google**:

### General

-   What is source code management
-   What is Git
-   What is GitHub
-   What is the difference between Git and GitHub
-   How to create a repository
-   What is a README
-   How to write good READMEs
-   How to commit
-   How to write helpful commit messages
-   How to push code
-   How to pull updates
-   How to create a branch
-   How to merge branches
-   How to work as collaborators on a project
-   Which files should and which files should not appear in your repo

### Copyright - Plagiarism

-   You are tasked to come up with solutions for the tasks below yourself to meet with the above learning objectives.
-   You will not be able to meet the objectives of this or any following project by copying and pasting someone else's work.
-   You are not allowed to publish any content of this project.
-   Any form of plagiarism is strictly forbidden and will result in removal from the program.

Requirements
------------

### General

-   A `README.md` file at the root of the `alx-zero_day` repo, containing a description of the repository
-   A `README.md` file, at the root of the folder of *this* project (i.e. `0x03-git`), describing what this project is about
-   **Do not use GitHub's web UI**, but the command line to perform the exercise (except for operations that can not possibly be done any other way than through the web UI). You won't be able to perform many of the task requirements on the web UI, and you should start getting used to the command line for simple tasks because many complex tasks can only be done via the command line.
-   Your answer files should only contain the command, and nothing else

More Info
---------

### Basic usage

At the end of this project you should be able to reproduce and understand these command lines:

```
$ git clone <repo>
$ touch test
$ git add test
$ git commit -m "Initial commit"
$ git push origin main

```

### Quiz questions

**Great!** You've completed the quiz successfully! Keep going! (Show quiz)

Tasks
-----

### 0\. Create and setup your Git and GitHub account

mandatory

#### Step 0 - Create an account on GitHub [if you do not have one already]

You will need a GitHub account for all your projects at ALX. If you do not already have a github.com account, you can create an account for free [here](https://alx-intranet.hbtn.io/rltoken/1vpH3ScWYjfgZD0J59jusA "here")

#### Step 1 - Create a Personal Access Token on Github

To have access to your repositories and authenticate yourself, you need to create a Personal Access Token on Github.

You can follow [this tutorial](https://alx-intranet.hbtn.io/rltoken/ArBVmv-Vj5ZsEnOutGy41A "this tutorial") to create a token.

Once it's created, you should have a token that looks like this:

![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2022/2/a449483cd76a72cef1b42df831e686c64faa1cf6.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20220830%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220830T074032Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=04ae324f06036b4ed68e29887aef88979bf53d2ebe972e781e6a5031804afcc2)

#### Step 2 - Update your profile on the Intranet

Update your Intranet profile by adding your Github username [here](https://alx-intranet.hbtn.io/rltoken/9dthiwx9AyxxUzV_QPIRWQ "here")

If it's not done **the Checker won't be able to correct your work**

![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2022/2/6270480a0a982cd1846b877eda2ee405d2e8f575.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20220830%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220830T074032Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=e3cec342c6ec79860a39c365da23068baae6c9d8948884c95422f74d05bf9b4b)

#### Step 3 - Create your first repository

Using the graphic interface on the [github website](https://alx-intranet.hbtn.io/rltoken/1vpH3ScWYjfgZD0J59jusA "github website"), create your first repository.

-   Name: `alx-zero_day`
-   Description: `I'm now a ALX Student, this is my first repository as a full-stack engineer`
-   Public repo
-   No `README`, `.gitignore`, or license

![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2022/2/2340a2d0f7c74b5dd6f8fc2aa58f94d13ea2c775.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20220830%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220830T074032Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=24b4cc98cc21cfb8639619edcdb3e863947eff89310a8800b341c9db9ea5daa9)

#### Step 4 - Open the sandbox

On the intranet, just under the task, click on the button ![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2022/2/9db8eece71455dfddf4b7d8585c037c535f1d18d.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20220830%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220830T074032Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=918816a51af59cdb3301566f09470a589f013124cbd8e20209481474c94db6f7) and `run` to start the machine.

Once the container is started, click on ![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2022/2/be9d1fbfb3d97e6924a4d2af7df9290ad7ae77df.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20220830%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220830T074032Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=e8a2b6a434edd65e715f24cf2e20ea190fab87a5f4d63310cfefb708b77fae20) to open a shell where you can start work from.

#### Step 5 - Clone your repository

On the webterm of the sandbox, do the following:

-   Clone your repository

```
root@896cf839cf9a:/# git clone https://{YOUR_PERSONAL_TOKEN}@github.com/{YOUR_USERNAME}/alx-zero_day.git
Cloning into 'alx-zero_day'...
warning: You appear to have cloned an empty repository.

```

**Replace {YOUR_PERSONAL_TOKEN} with your token from step 1**

**Replace {YOUR_USERNAME} with your username from step 0 and 1**

**Pro-Tip:** On windows, use CTRL + A + V to paste in the web terminal

#### Step 6 - Create the README.md and push the modifications

-   Navigate to this new directory. [Tips](https://alx-intranet.hbtn.io/rltoken/qSP5HcBSSIL0U23PdIGKLw "Tips")

```
root@896cf839cf9a:/# cd alx-zero_day/
root@896cf839cf9a:/alx-zero_day#

```

-   Create the file `README.md` with the content `My first readme`. [Tips](https://alx-intranet.hbtn.io/rltoken/_SSotigVtvVNThTVLJKZPQ "Tips")

```
root@896cf839cf9a:/alx-zero_day# echo 'My first readme' > README.md
root@896cf839cf9a:/alx-zero_day# cat README.md
My first readme

```

-   Update your git identity

```
root@896cf839cf9a:/alx-pre_course# git config --global user.email "you@example.com"
root@896cf839cf9a:/alx-pre_course# git config --global user.name "Your Name"

```

-   Add this new file to git, commit the change with this message "My first commit" and push to the remote server / origin

```
root@896cf839cf9a:/alx-zero_day# git add .
root@896cf839cf9a:/alx-zero_day# git commit -m 'My first commit'
[master (root-commit) 98eef93] My first commit
 1 file changed, 1 insertion(+)
 create mode 100644 README.md
root@896cf839cf9a:/alx-zero_day# git push
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 212 bytes | 212.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/{YOUR_USERNAME}/alx-zero_day.git
 * [new branch]      master -> master

```

Good job!

You pushed your first file in your **first repository** of the **first task** of your **first ALX School project**.

You can now check your repository on GitHub to see if everything is good.

**Repo:**

-   GitHub repository: `alx-zero_day`
-   File: `README.md`

 Done? Help Check your code Get a sandbox

### 1\. Repo-session

mandatory

Create a new directory called `0x03-git` in your `alx-zero_day` repo.

Make sure you include a not empty `README.md` in your directory:

-   at the root of your repository `alx-zero_day`
-   AND in the directory `0x03-git`

And important part: **Make sure your commit and push your code to Github - otherwise the Checker will always fail.**

**Repo:**

-   GitHub repository: `alx-zero_day`

 Done? Help Check your code Get a sandbox

### 2\. Coding fury road

mandatory

For the moment we have an empty project directory containing only a `README.md`. It's time to code!

-   Create these directories at the root of your project: `bash`, `c`, `js`
-   Create these empty files:
    -   `c/c_is_fun.c`
    -   `js/main.js`
    -   `js/index.js`
-   Create a file `bash/alx` with these two lines inside: `#!/bin/bash` and `echo "ALX"`
-   Create a file `bash/school` with these two lines inside: `#!/bin/bash` and `echo "School"`
-   Add all these new files to git
-   Commit your changes (message: "Starting to code today, so cool") and push to the remote server

**Repo:**

-   GitHub repository: `alx-zero_day`
-   Directory: `0x03-git`
-   File: `bash/alx, bash/school, c/c_is_fun.c, js/main.js, js/index.js`

 Done? Help Check your code Get a sandbox

### 3\. Collaboration is the base of a company

mandatory

A branch is like a copy of your project. It's used mainly for:

-   adding a feature in development
-   collaborating on the same project with other developers
-   not breaking your entire repository
-   not upsetting your co-workers

The purpose of a branch is to isolate your work from the main code base of your project and/or from your co-workers' work.

For this project, create a branch `update_script` and in this branch:

-   Create an empty file named `bash/98`
-   Update `bash/alx` by replacing `echo "ALX"` with `echo "ALX School"`
-   Update `bash/school` by replacing `echo "School"` with `echo "The school is open!"`
-   Add and commit these changes (message: "My personal work")
-   Push this new branch [Tips](https://alx-intranet.hbtn.io/rltoken/tN31xFfDVctixZZ350tDGw "Tips")

Perfect! You did an amazing update in your project and it's isolated correctly from the **main** branch.

Ho wait, your manager needs a quick fix in your project and it needs to be deployed now:

-   Change branch to `main`
-   Update the file `bash/alx` by replacing `echo "ALX"` with `echo "ALX School is so cool!"`
-   Delete the directory `js`
-   Commit your changes (message: "Hot fix") and push to the origin

Ouf, hot fix is done!

**Repo:**

-   GitHub repository: `alx-zero_day`
-   Directory: `0x03-git`
-   File: `bash/alx, bash/school, bash/98`

 Done? Help Check your code Get a sandbox

### 4\. Collaboration: be up to date

mandatory

Of course, you can also work on the same branch as your co-workers and it's best if you keep up to date with their changes.

For this task -- **and only for this task** -- please update your file `README.md` in the main branch from GitHub.com. It's the **only time** you are allowed to update and commit from GitHub interface.

After you have done that, in your terminal:

-   Get all changes of the main branch locally (i.e. your `README.md` file will be updated)
-   Create a new file `up_to_date` at the root of your directory and in it, write the git command line used
-   Add `up_to_date` to git, commit (message: "How to be up to date in git"), and push to the origin

**Repo:**

-   GitHub repository: `alx-zero_day`
-   Directory: `0x03-git`
-   File: `README.md, up_to_date`

 Done? Help Check your code Get a sandbox

[Done with the mandatory tasks? Unlock 2 advanced tasks now!](https://alx-intranet.hbtn.io/projects/1/unlock_optionals)

Copyright © 2022 ALX, All rights reserved.
