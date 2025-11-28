<div align="center"><img src="https://github.com/vtiquet/holbertonschool-resources/blob/main/image/Holberton-Logo.svg" width=40% height=40%/></div>

# Resources

## Table of Contents :

  - [0. Create and setup your Git and GitHub account](#subparagraph0)
  - [1. Repo-session](#subparagraph1)
  - [2. Coding fury road](#subparagraph2)
  - [3. Collaboration is the base of a company](#subparagraph3)
  - [4. Collaboration: be up to date](#subparagraph4)
  - [5. HAAA what did you do???](#subparagraph5)
  - [6. Never push too much](#subparagraph6)

## Resources
### Read or watch:
* [Resources to learn Git](/rltoken/P_HNOwBGwzvG1ZyrzKoA2A)
* [About READMEs](/rltoken/isqOS_q7Vg7y6WcbVPS9HQ)
* [How to write a Git commit message](/rltoken/HC4g5kW0LGBSswOS5LsDYQ)

## Learning Objectives
At the end of this project, you are expected to be able to explain to anyone, without the help of Google:
* What is source code management
* What is Git
* What is GitHub
* What is the difference between Git and GitHub
* How to create a repository
* What is a README
* How to write good READMEs
* How to commit
* How to write helpful commit messages
* How to push code
* How to pull updates
* How to create a branch
* How to merge branches
* How to work as collaborators on a project
* Which files should and which files should not appear in your repo

## Requirements
### General
* AREADME.mdfile at the root of the repo, containing a description of the repository
* AREADME.mdfile, at the root of the folder ofthisproject (i.e.git), describing what this project is about
* Do not use GitHub’s web UI, but the command line to perform the exercise (except for operations that can not possibly be done any other way than through the web UI). You won’t be able to perform many of the task requirements on the web UI, and you should start getting used to the command line for simple tasks because many complex tasks can only be done via the command line.
* Your answer files should only contain the command, and nothing else

## Task
### 0. Create and setup your Git and GitHub account <a name='subparagraph0'></a>

You will need a GitHub account for all your projects. You can create an account for free  <a href="/rltoken/-mliVC8UBjdpAGbt2IKWTQ" target="_blank" title="here">here</a>

To have access to your repositories and authenticate yourself, you need to create a Personal Access Token on Github.

You can follow <a href="/rltoken/7jjq1lWDPmYnWsM2EjxvsQ" target="_blank" title="this tutorial">this tutorial</a> to create a token.

Once it’s created, you should have a token that looks like this:

<img alt="" loading="lazy" src="https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2022/2/5324a3dea7703623ea16353796ee5dcc82514391.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&amp;X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20251128%2Feu-west-3%2Fs3%2Faws4_request&amp;X-Amz-Date=20251128T081927Z&amp;X-Amz-Expires=86400&amp;X-Amz-SignedHeaders=host&amp;X-Amz-Signature=90f979e512c5fb1c0cccaab56510e2d059ac9bcd0693d25aea859fc52fc46a0a" style="width: 500px"/>

Update your Intranet profile by adding your Github username <a href="/rltoken/FwTaZlU2qLyPNVwkKAnX9w" target="_blank" title="here">here</a>

If it’s not done <strong>the Checker won’t be able to correct your work</strong>

<img alt="" loading="lazy" src="https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2022/2/0d6755d000841c87ad2bf7e62f648b64e0f6abc1.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&amp;X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20251128%2Feu-west-3%2Fs3%2Faws4_request&amp;X-Amz-Date=20251128T081927Z&amp;X-Amz-Expires=86400&amp;X-Amz-SignedHeaders=host&amp;X-Amz-Signature=b8cd2810fb4f84334363ccb30c08e03c4431f54c70e5eec937504fa7f498623b" style="width: 400px"/>

Using the graphic interface on the <a href="/rltoken/-mliVC8UBjdpAGbt2IKWTQ" target="_blank" title="github website">github website</a>, create your first repository.

* <strong>Name: Look at the bottom of this TASK to see the name of the repository</strong> <- <strong>PAY ATTENTION TO THIS</strong>
* Description: <code>This is my first repository as a full-stack engineer</code>
* Public repo
* No <code>README</code>, <code>.gitignore</code>, or license

<img alt="" loading="lazy" src="https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2022/2/129da22e07db4f6ccbd715687d18b5179359ba38.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&amp;X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20251128%2Feu-west-3%2Fs3%2Faws4_request&amp;X-Amz-Date=20251128T081927Z&amp;X-Amz-Expires=86400&amp;X-Amz-SignedHeaders=host&amp;X-Amz-Signature=5e4d82017479247788dacd4166d4733986cde6f1fd2bb1f8699aa4dd11261f1d" style="width: 400px"/>

On the intranet, just under the task, click on the button <img alt="" loading="lazy" src="https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2022/2/007c351c13148e0c4c04528c7aed7cea0982ebb1.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&amp;X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20251128%2Feu-west-3%2Fs3%2Faws4_request&amp;X-Amz-Date=20251128T081927Z&amp;X-Amz-Expires=86400&amp;X-Amz-SignedHeaders=host&amp;X-Amz-Signature=b9f2019428ee538ec590816f26da65e37656233e710b5ec1b825c55d75654a8b" style="width: 100px"/> and <code>run</code> to start the machine.

Once the container is started, click on <img alt="" loading="lazy" src="https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2022/2/ff8ebf0b6ef71fd3e9d0f03bfd560b7483e45d91.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&amp;X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20251128%2Feu-west-3%2Fs3%2Faws4_request&amp;X-Amz-Date=20251128T081927Z&amp;X-Amz-Expires=86400&amp;X-Amz-SignedHeaders=host&amp;X-Amz-Signature=61de7dd295fec101ad838c0941620ec29dd250dccc5bb0c6bbfb644a77560f93" style="width: 100px"/> or on <img alt="" loading="lazy" src="https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2024/2/c3be4d7065015595148b32c6add147abf32d04d7.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&amp;X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20251128%2Feu-west-3%2Fs3%2Faws4_request&amp;X-Amz-Date=20251128T081927Z&amp;X-Amz-Expires=86400&amp;X-Amz-SignedHeaders=host&amp;X-Amz-Signature=317d55d064538b6e39cfe23a5ecb29fee008e51b957b791617525d1acd9d06c6" style=""/> (for the new sandboxes) to open a shell where you can start work from.

On the webterm of the sandbox, do the following:

* Clone your repository

```
root@896cf839cf9a:/# git clone https://{YOUR_PERSONAL_TOKEN}@github.com/{YOUR_USERNAME}/{YOUR_REPO}.git                  
Cloning into '{YOUR_REPO}'...
warning: You appear to have cloned an empty repository.
```

<strong>Replace {YOUR_PERSONAL_TOKEN} with your token from step 1</strong>

<strong>Replace {YOUR_USERNAME} with your username from step 0 and 1</strong>

<strong>Replace {YOUR_REPO} with the name of the repository at the bottom of the task</strong>

* Navigate to this new directory. <a href="/rltoken/qmCUqDSM0xK-uTjWEUn4fg" target="_blank" title="Tips">Tips</a>

```
root@896cf839cf9a:/# cd {YOUR_REPO}/
root@896cf839cf9a:/{YOUR_REPO}#
```

-Create the file <code>README.md</code> with the content <code>My first readme</code>. <a href="/rltoken/aHozN0Vh670Y66k_C8rCMg" target="_blank" title="Tips">Tips</a>

```
root@896cf839cf9a:/{YOUR_REPO}# echo 'My first readme' > README.md                                                                 
root@896cf839cf9a:/{YOUR_REPO}# cat README.md                                                                                      
My first readme
```

* Add this new file to git, commit the change with this message “My first commit” and push to the remote server / origin

```
root@896cf839cf9a:/{YOUR_REPO}# git add .
root@896cf839cf9a:/{YOUR_REPO}# git commit -m 'My first commit'
[master (root-commit) 98eef93] My first commit
 1 file changed, 1 insertion(+)
 create mode 100644 README.md
root@896cf839cf9a:/{YOUR_REPO}# git push                                                                                           
Enumerating objects: 3, done.                                                                                                         
Counting objects: 100% (3/3), done.                                                                                                   
Writing objects: 100% (3/3), 212 bytes | 212.00 KiB/s, done.                                                                          
Total 3 (delta 0), reused 0 (delta 0)                                                                                                 
To https://github.com/{YOUR_USERNAME}/{YOUR_REPO}.git                                                                                       
 * [new branch]      master -> master
```

Good job!

You pushed your first file in your <strong>first repository</strong>.

You can now check your repository on GitHub to see if everything is good.

---

### 1. Repo-session <a name='subparagraph1'></a>

Create a new directory called <code>git</code> in your repo.

Make sure you include a not empty <code>README.md</code> in your directory:

* at the root of your repository
* AND in the directory <code>git</code>

And important part: <strong>Make sure your commit and push your code to Github - otherwise the Checker will always fail.</strong>

---

### 2. Coding fury road <a name='subparagraph2'></a>

For the moment we have an empty project directory containing only a <code>README.md</code>. It’s time to code!

* Create these directories in the <code>git</code> folder: <code>bash</code>, <code>c</code>, <code>js</code>
* Create these empty files:


  * <code>c/c_is_fun.c</code>
  * <code>js/main.js</code>
  * <code>js/index.js</code>
* Create a file <code>bash/best</code> with these two lines inside: <code>#!/bin/bash</code> and <code>echo "Best"</code>
* Create a file <code>bash/school</code> with these two lines inside: <code>#!/bin/bash</code> and <code>echo "School"</code>
* Add all these new files to git
* Commit your changes (message: “Starting to code today, so cool”) and push to the remote server

---

### 3. Collaboration is the base of a company <a name='subparagraph3'></a>

A branch is like a copy of your project. It’s used mainly for:

* adding a feature in development
* collaborating on the same project with other developers
* not breaking your entire repository
* not upsetting your co-workers

The purpose of a branch is to isolate your work from the main code base of your project and/or from your co-workers’ work.

For this project, create a branch <code>update_script</code> and in this branch:

* Create an empty file named <code>bash/98</code>
* Update <code>bash/best</code> by replacing <code>echo "Best"</code> with <code>echo "Best School"</code>
* Update <code>bash/school</code> by replacing <code>echo "School"</code> with <code>echo "The school is open!"</code>
* Add and commit these changes (message: “My personal work”)
* Push this new branch <a href="/rltoken/8yF25ELfCKWR1WekJGw8vA" target="_blank" title="Tips">Tips</a>

Perfect! You did an amazing update in your project and it’s isolated correctly from the <strong>main</strong> branch.

Oh wait, your manager needs a quick fix in your project and it needs to be deployed now:

* Change branch to <code>main</code>
* Update the file <code>bash/best</code> by replacing <code>echo "Best"</code> with <code>echo "This School is so cool!"</code>
* Delete the directory <code>js</code>
* Commit your changes (message: “Hot fix”) and push to the origin

Ouf, hot fix is done!

---

### 4. Collaboration: be up to date <a name='subparagraph4'></a>

Of course, you can also work on the same branch as your co-workers and it’s best if you keep up to date with their changes.

For this task – <strong>and only for this task</strong> – please update your file <code>README.md</code> in the main branch from GitHub.com. It’s the <strong>only time</strong> you are allowed to update and commit from GitHub interface.

After you have done that, in your terminal:

* Get all changes of the main branch locally (i.e. your <code>README.md</code> file will be updated)
* Create a new file <code>up_to_date</code> in the project directory (<code>git</code>) and in it write the git command line used
* Add <code>up_to_date</code> to git, commit (message: “How to be up to date in git”), and push to the origin

---

### 5. HAAA what did you do??? <a name='subparagraph5'></a>

Collaboration is cool, but not really when you update the same file at the same time…

To illustrate that, please merge the branch <code>update_script</code> to <code>main</code>: “Cool, all my changes will be now part of the main branch, ready to be deployed!”

<strong>HHHHHHHAAAAAAAA</strong>

```
CONFLICT (content): Merge conflict in bash/best
```

As you can see, you have conflicts between two branches on the same file.

Your goal now is to resolve conflicts by using the version of the branch <code>update_script</code>, and push the result to the origin.

At the end, you should have all your work from the branch <code>update_script</code> (new file and two updated files) and all latest <code>main</code> commits (new files, delete folder, etc.), <em>without</em> conflicts.

---

### 6. Never push too much <a name='subparagraph6'></a>

Create a <code>.gitignore</code> file and define a rule to never push <code>~</code> files (generated by Emacs). <a href="/rltoken/g6VBA-IZb-lfYWv75-urIw" target="_blank" title="Tips">Tips</a>

---


## Authors
vtiquet - [GitHub Profile](https://github.com/vtiquet)
