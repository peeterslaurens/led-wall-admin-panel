# [PROJECT-NAME] v1.0.0
Short description of the project.


# Table of contents #

* [Setup](#setup)
    * [System Dependencies](#system-dependencies)
    * [Init](#init)
* [Code Contribution](#code-contribution)
    * [Branches](#branches)
* [Environments](#environments)
* [Project Context](#project-context)
    * [Details](#details)
    * [Team](#team)



## Setup

### System Dependencies
* List the system dependencies here.
* Make sure to keep in mind that NPM packages that can be installed locally, should be installed locally.
* E.g. [MongoDB 3.4.4](https://www.mongodb.com/)
* E.g. [Node 6.10.2](https://nodejs.org/en/)

### Init
* List the actions that are required to run the project
* `nvm use` [Check out NVM AutoSwitch](https://github.com/lalitkapoor/nvm-auto-switch)
* `npm i`


## Code Contribution

### Branches

We follow these naming conventions:

* **master**
* **develop**
* **release/***:
* **feature/***
* **bugfix/***
* **hotfix/***: Used only for hotfixing critical bugs from the `master`-branch.




## Environments

### Development
The development environment receives automatic builds when code is contributed to the `development`-branch. This environment is expected to break from time to time and thus should be used for **internal testing only**!

**URL**: [https://bitbucket.org/district01/boilerplate/overview](https://bitbucket.org/district01/boilerplate/overview)

### Staging
The staging environment receives automatic builds when code is contributed to the `master`-branch. This environment is expected to remain stable and should be used for **client validation testing**.

**URL**: [https://bitbucket.org/district01/boilerplate/overview](https://bitbucket.org/district01/boilerplate/overview)

### Production
The production environment is built manually from the `master`-branch. This environment has to be **stable at all times**. No unvalidated code can be deployed on this environment.

**URL**: [https://bitbucket.org/district01/boilerplate/overview](https://bitbucket.org/district01/boilerplate/overview)



## Project Context
This project is a New-Media team effort.

### Details
* **Client**: Digipolis
* **Start**: 12/10/2017
* **Jira Board**: http://www.district01.be
* **Drive Folder**: http://www.district01.be
* **Project Sheet**: http://www.district01.be

### Team
List the team that has worked on this project, including the duration e.g.:

* [Fabian Meul - District01](fabian.meul@district01.be)
    * **Function**: Lead Front-End Dev
    * **Period**: October 2017 -> December 2017
* [Thomas Bormans - District01](fabian.meul@district01.be)
    * **Function**: Lead Technical Dev
    * **Period**: October 2017 -> December 2017
