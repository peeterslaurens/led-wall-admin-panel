# [PROJECT-NAME] #

# Table of contents #

   * [[PROJECT-NAME]](#project-name)
   * [Table of contents](#table-of-contents)
   * [Setup of the repository](#setup-of-the-repository)
      * [Guidelines for the owner](#guidelines-for-the-owner)
      * [Guidelines for all team members](#guidelines-for-all-team-members)
   * [Best practices](#best-practices)
      * [npm scripts](#npm-scripts)
   * [What is this repository for?](#what-is-this-repository-for)
   * [How do I get set up?](#how-do-i-get-set-up)
   * [Which scripts are available?](#which-scripts-are-available)
   * [Contribution guidelines](#contribution-guidelines)
   * [Who do I talk to?](#who-do-i-talk-to)
   * [Contributing to the boilerplate](#contributing-to-the-boilerplate)
      * [Create an issue](#create-an-issue)
      * [Open pull request](#open-pull-request)

# Setup of the repository #

## Guidelines for the owner ##

* Fill in the Projectsheet on Google Drive
* Enter all the necessary information in the README.md
    * What is this repository for?
    * Quick summary?
    * How do I get set up?
    * Summary of set up?
    * Which scripts are available?
    * Contribution guidelines
    * Who do I talk to?
    * Table of contents (can easily be done with [github-markdown-toc])
* Update package.json
    * name
    * version
    * homepage
    * projectsheet url
* Have fun coding

## Guidelines for all team members ##

* Add yourself to the _Who do I talk to?_ list in this file (at the bottom)
* Go through the README.md and complete where necessary
* Have fun coding

# Best practices #

## npm scripts ##

Add as much dependencies to the package.json instead of relying on globally installed packages.

E.g.: If you are configuring an eslint task, add eslint as dev dependency. You will be able to run eslint by executing `./node_modules/.bin/eslint`.

**Please note:** Not every executable is available in _./node_modules/.bin/_. For easier development it is advised to add the command as npm script. Instead of using _./node_modules/.bin/_, you can use _npm-run_ in your script. This means that `./node_modules/.bin/eslint` becomes `npm-run eslint`. Checkout the _package.json_ file for more examples.

# What is this repository for? #

* Quick summary
* Version (should be the same as the `package.json` version)

# How do I get set up? #

* Summary of set up
* Configuration
* Dependencies
    * Software X
    * Software Y
* Database configuration
* How to run linter(s)
* How to run tests
* Deployment instructions
* Environments
    * [development][development-url]
    * [staging][staging-url]
    * [production][production-url]
* Extra information

# Which scripts are available? #

| Command       | Description                                 |
| ------------- |-------------------------------------------- |
| clean         | Remove the dist folder.                     |
| projectsheet  | Open the projectsheet on Google Drive       |
| pm2           | Run the project with pm2                    |
| nodemon       | Run the project with nodemon                |
| watch         | Run all the watch tasks                     |
| watch:css     | Watch for sass changes and build css        |
| watch:images  | Watch for image changes and compile images  |
| lint          | Run all the lint tasks                      |
| lint:eslint   | Run eslint                                  |
| lint:tslint   | Run tslint lint                             |
| lint:sass     | Run sass lint                               |
| serve         | Serve the current project on port 86666     |
| build         | Run all the build tasks                     |
| build:ts      | Build typescript                            |
| build:css     | Build sass                                  |
| build:images  | Compile images                              |
| fixtures      | Seed the database                           |
| ...           | ...                                         |

All commands are executable by running `npm run [COMMAND-NAME]`.

# Contribution guidelines #

* Writing tests
* Code review
* Other guidelines

# Who do I talk to? #

* Repo owner or admin (email)
* Other team members (email)

# Contributing to the boilerplate #

This repository is forked from the Front End Ops [boilerplate]. The template consists of these repositories:
* [editorconfig]
* [gitignore]
* [script-linting]
* [style-linting]

## Create an issue ##

If you find a bug in one of these repositories, have trouble following the documentation or have a question about the project – create an issue! There's nothing to it and whatever issue you're having, you're likely not the only one, so others will find your issue helpful, too.

## Open pull request ##

If you're able to patch the bug or add the feature yourself – fantastic, make a pull request with the code! Be sure you've read any documents on contributing. Once you've submitted a pull request the maintainer(s) can compare your branch to the existing one and decide whether or not to incorporate (pull in) your changes.


[//]: # (All links should be included below)

   [//]: # (Url's where the project can be found)
   [development-url]: <https://bitbucket.org/district01/boilerplate/overview>
   [staging-url]: <https://bitbucket.org/district01/boilerplate/overview>
   [production-url]: <https://bitbucket.org/district01/boilerplate/overview>

   [//]: # (Front End Ops repositories)
   [Issues guide]: <https://bitbucket.org/district01/boilerplate/issues?status=new&status=open>
   [boilerplate]: <https://bitbucket.org/district01/boilerplate>
   [editorconfig]: <https://bitbucket.org/district01/editorconfig>
   [gitignore]: <https://bitbucket.org/district01/gitignore>
   [machine-setup]: <https://bitbucket.org/district01/machine-setup>
   [npm-scripts]: <https://bitbucket.org/district01/npm-scripts>
   [script-linting]: <https://bitbucket.org/district01/script-linting>
   [style-linting]: <https://bitbucket.org/district01/style-linting>

   [//]: # (Miscellaneous)
   [github-markdown-toc]: <https://github.com/ekalinin/github-markdown-toc>