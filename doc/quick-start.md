---
title: Quick Start
menuOrder: 1
autotoc: true
---

# Quick Start

**Enlight'me** is a very simple static site generator that can help you to
build your application / library documentation easily. This document will show
you the basics to generate your first Enlight'me site in **only 5 minutes**.


## Installing Enlight'me

First of all, install Enlight'me on your computer (we assume you have already
installed Node.js and NPM):

    npm install -g enlightme

That's it for the installation.


## Creating Your First Enlight'me Site

Creating your Enlight'me-generated documentation website requires only 3 (short
and easy) steps described bellow.

### 1. Write Some Markdown Files

First of all, you have to write your documentation in the [Markdown][gfm] format:

* Create a `doc/` folder at the root of your project,
* Write some Markdown files in it,
* and you're done!

**Example:**

    MyProject/
        |
        +-- doc/
        |   |
        |   o-- index.md
        |   |
        |   o-- quick-start.md
        |
        o-- package.json


### 2. Generate The site

To generate the HTML version of your site, just type the following command:

    enlightme

The generated content is created in the `doc.generated/` folder, located at
the root of your project.

__TIP:__ you can add this folder to your `.gitignore` file to avoid committing
it accidentally.

### 3. Publish to Github Pages

Publishing the site on your [Github Pages][gh-pages] can be done with the following command:

    enlightme publish

Your site is now online. Wow, way too easy isn't it?


[gfm]: https://guides.github.com/features/mastering-markdown/
[gh-pages]: https://pages.github.com/
