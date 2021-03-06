﻿Jonathan - Kevin - Perrine

# THE WORKFLOW

A **workflow** consists of an orchestrated and repeatable pattern of business activity.
About our activity we tried few of them.

1.  To begin, we decide to use **the pair programming**. It consists to share the same computer in a given time (10 minutes for each one) to create code.

        	- Pros:
        		- conflicts happened before we write the code. So no conflicts on pull requests.
        		- it's a good way to learn other coding styles and tricks.
        	- Cons:
        		- it's a waste of time in term of productivity.

2.  After it, we decide to work on the same branch but each one of us using his computer. - Pros: - better comfort for us because it's our computer. - we don't have to wait for team mates. - Cons: - lot of conflicts to resolve each time we push. - risk to loose your progress.

3.  To finish, we try to create different branches for each feature. - Pros: - same pros as before. - we always have a stable version of the project. - no push conflict, only one when we merge. - when pull request, the team mates have to validate the new code. - Cons: - it's difficult to understand and to set for a beginner.

To conclude, each one can prefer his workflow, but we don't recommend the second one.
We've got only problems with it, and no pros.
Weekly report - 03/03/2019

Team: Vanessa Salvador, Nizar Slama, Florian Gardy
Topic: GitHub pages
What is GitHub pages

# Fonctionnalities bootstrap

### What is bootstrap

It is a front-end infrastructure for quickly and aesthetically creating a site / webpages / application through an open source library and toolkit.
It was created and managed by Twitter to meet an internal need of the team. This is the most used CSS framework.
It uses a responsive grid system, many predefined components, and powerful jQuery-based plug-ins.
We used it as part of a group project to create one or more pages of a blog.

### How to use it?

In order to use this library there are several methods: CDN or download.

#### 1. BootstrapCDN: What's this?

A Content Delivery Network (CDN) is a set of servers located at different locations and networked via the internet.
It is necessary to Copy-Paste a <link> into your <head> and place
the <script> near the end of your pages, just before the </ body> closing tag.

#### 2. Other methods:

Bootstrap components can be downloaded directly to their site.

### How it works?

Bootstrap uses a responsive 12 column grid layout and has design templates for:

-   Buttons
-   Images
-   Tables
-   Forms
-   Navigation

### Pros and Cons:

#### Pros:

-   Quick site layout ;
-   Very flexible, possibility of modifying the code directly in the HTML ;
-   Render quickly very aesthetic;

#### Cons:

-   Sites necessarily identical at the level of the structure, due to the Bootstrap standard;
-   The copy-pasted;
-   Some tools are difficult to modify at our choice.


# GitHub Pages

## What is GitHub pages

GitHub Pages is a service, provided by GitHub, designed to host your personal, organization, or project pages directly from a GitHub repository.


## How to publish on GitHub Pages ?

If you want to publish a website **as a standard user or an organization**, simply create a new repository on GitHub named **username.github.io**, where _username_ is your username (or organization name) on GitHub.
All the modifications done on the master branch are automatically published on internet.

If you want to publish a **project site**:
 - create any repository
 - create/add a file "index.html"
 - modify the settings of the repository: Settings > GitHub Pages > Select the source branch (master)
 Your site will be publish after your next commit on the master branch.

  
## How can I reach my website ?

To reach your web site, open any web browser and open the url pattern below:
**User or organization** : https://*username*.github.io
**Project** : http://*username*.github.io/*repository*



**Crew:*** Amine, Sarah, Stéphane


# Management Conflicts

**

## How to resolve merge conflicts**

**

3 merge tools :

1. - Visual Studio

2. - Meld: via Git

3. - Github : Pull request***


## **1= VISUAL STUDIO**

		-The conflicts begin when you make a git pull (we are on a dev branch)
		-Visual Studio display red stickers = conflict indicators
		-Display between the remote code and your local code:  
		*An input mode with a color and an output mode with another color* 
		-As long as the conflicts are not settled, no further action can be allow
		-Choose the code that we want to keep and validate
		-3 possible options = accept both changes / accept incoming changes / accept current changes
		-After that, make a git push on the current branch (dev)

*Warning!*  
One piece of advice: start conflict management from the bottom of the code page to avoid validating all conflicts without being able to check them one by one.

*VS Screenshots*
(https://code.visualstudio.com/assets/docs/editor/versioncontrol/merge-conflict.png)
![RÃ©sultat de recherche d'images pour "visual studio code merge tool"](https://code.visualstudio.com/assets/docs/editor/versioncontrol/overview.png)


## **2= MELD**

When using Git, "git mergetool" will start a 'merge helper
3 parts displayed:
1- Local code
2- Code commit
3- Remote code
- Allow to have a global visualization of the differences between local, remote and commit code.
- Choose the code that you want to keep for the project (thanks to the arrow button)
- Save the choice and it's done.

*Meld Screenshot*
![RÃ©sultat de recherche d'images pour "meld screenshots"](https://i.stack.imgur.com/QRzUR.png)

## **3= GITHUB**

-Go on the repository on Github
-Choose the branch which will receive the data
-The branch where the data came from
-Make a pull request
-Add a comment if needed
-Check the message: Indicator able to merge or not
-And do the validation.

*Only the repository owner can do the validation*

https://chat.wildcodeschool.fr/file-upload/yZGkrZokLYNQurrWB/Capture%20d%E2%80%99%C3%A9cran%20de%202019-03-08%2011-23-15.png



** Conclusion **: Conflict management on a daily basis and throughout the project is **highly* recommended**.
Thus you can save time and avoid being overwhelmed by too much conflict at the end of the project.


WILD CODE SCHOOL WEEK 2
====
BOOTSTRAP
===
Bootstrap is a Framework for design creation on websites. Bootstrap  notably allows to make a responsive design thinking mobile first.

 It's a library which contains various tools based on grid system.
It uses a series of containers, rows, and columns to layout and align content. It’s built with flexbox and is fully responsive.
Bootstrap's grid function with a 12 columns system : we need to use bootstrap's classes to position elements on the page.

The Bootstrap installation can be done in CDN and the library via a Javascript link on the HTML page as well as a link for the importer CSS related to Bootstrap. The installation can also be done by installing the files locally on his computer.

Besides Bootstrap propose different elements to build  website pages : 

* Layout
* Components:
Bootstrap contains differents components in the library (buttons, Navbar, list-group etc.). . . 
We can take different éléments and merge them.

* Content : images, tables, figures, etc.


GRID SYSTEM
---
Using the grid system facilitates communication between different trades (web designers, developers, etc.) during the creation of a website. It allows you to create layouts by dividing the display space into usable regions to position multiple items.

FLEXBOX
---

The principle of layout with Flexbox is simple: you define a container, and inside you place several elements that can be positioned uni directionally in this container.


Stéphane - Marlène - Cloé