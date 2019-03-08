Jonathan - Kevin - Perrine

THE WORKFLOW

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

GitHub Pages is a service, provided by GitHub, designed to host your personal, organization, or project pages directly from a GitHub repository.
How to publish on GitHub Pages ?

If you want to publish a website as a standard user or an organization, simply create a new repository on GitHub named username.github.io, where username is your username (or organization name) on GitHub.
All the modifications done on the master branch are automatically published on internet.

If you want to publish a project site:

    create any repository
    create/add a file “index.html”
    modify the settings of the repository: Settings > GitHub Pages > Select the source branch (master)
    Your site will be publish after your next commit on the master branch.

How can I reach my website ?

To reach your web site, open any web browser and open the url pattern below:
User or organization : https://username.github.io
Project : http://username.github.io/repository

> Written with [StackEdit](https://stackedit.io/).
