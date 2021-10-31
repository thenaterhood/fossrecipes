fossrecipes.com
-----------------

This is the backing git repository for [fossrecipes.com](http://fossrecipes.com), which contains recipes from the free and open source family.

This is a static website powered by Jekyll. See the licenses file
for details on licenses.

Contributing
-----------------
By contributing, you agree that your contributions will
fall under the same licenses as the rest of the content, AND
that you have the rights to contribute that material.


_In a nutshell_
* Fork this git repository to your own account
* Make your changes
* Create a pull request back to this repository
* Your changes will be reviewed and merged

Recipes:
* Located in the \_recipes folder in markdown format
* Please structure recipes as follows:
<pre>
---
title: The name of your recipe
tags: [tags, that, apply, to, your recipe]
layout: page
---

## Ingredients
* A list of your ingredients and quantities

## Utensils
* Any utensils required

## Directions
The instructions for making it
</pre>

## Dev environment

If you are using vscode, and have docker installed, reopen this project in a "Dev Container". It would load a jekyll working environment with the lastest jekyll and supported ruby versions.

[Learn more about Dev-Containers here](https://code.visualstudio.com/docs/remote/create-dev-container)

### Local Server

`jekyll serve --livereload --force-polling`

### Build

`JEKYLL_ENV=production bundle exec jekyll build`


Licenses
--------------
See the licenses file.

