# cli-weather

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc)*

- [Introduction](#introduction)
- [Installation] (#installation)
    - [Node.js](#node.js)
        - Alternatives
    - [Meow](#meow)
    - [Chalk](#chalk)
    - [Update-notifier](update-notifier)

## Introduction

An application that allow you to check the weather and temperature of a city.

##Installation
All the installations are using npm.
To check if you have Node.js installed, run this command in your terminal:
```sh
❯ node -v
```

To confirm that you have npm installed you can run this command in your terminal:
```sh
❯ npm -v
```

If not downloaded already, follow the following instructions
npm is distributed with Node.js- which means that when you download Node.js, you automatically get npm installed on your computer.

###Node.js ![node js_logo](https://cloud.githubusercontent.com/assets/22341176/23313374/b8a02dce-fabd-11e6-9d8b-92b14ff1768a.png)
Node.js is an open-source, cross-platform JavaScript runtime environment for developing a diverse variety of server tools and applications.

1. Install [Node.js](https://nodejs.org/en/).
2. Go ahead and run the downloaded installation file. It is recommended to use the default settings. Node.js needs to be added to the PATH environment variable, which is done by default.
3. To test the installation, open a command window (make sure you open a new command window to get the updated path settings made by the Node.js installation), and type:
```sh
❯ node --version
```
If the version number is displayed, Node.js is installed and working!

####Alternatives
It is possible to install Node.js using [Chocolatey](https://chocolatey.org/)
1. Install Chocolatery file.
2. Open a command window and type:
```sh
❯ cinst nodejs
  # or for full install with npm
❯ cinst nodejs.install
```
Or using [Scoop](http://scoop.sh/)
1. Requirements:
- [PowerSheel 3](https://www.microsoft.com/en-us/download/details.aspx?id=34595)
- PowerShell must be enabled for your user account e.g. set-executionpolicy remotesigned -s cu
To install:
```sh
❯ iex (new-object net.webclient).downloadstring('https://get.scoop.sh')
```
2. Open command line and type:
```sh
❯ scoop install curl
```

###[Meow](https://github.com/sumeetdas/Meow)
Meow is a NodeJS + AngularJS based blogging engine which is aimed at making blogs using AngularJS as front-end more easy to share and being crawled by various search bots.

```sh
❯npm install --save meow
```

###[Chalk](https://github.com/chalk/chalk/blob/master/readme.md) ![chalk_logo](https://cdn.rawgit.com/chalk/chalk/19935d6484811c5e468817f846b7b3d417d7bf4a/logo.svg)
colors.js used to be the most popular string styling module, but it has serious deficiencies like extending String.prototype which causes all kinds of problems. Although there are other ones, they either do too much or not enough.
Chalk is a clean and focused alternative.
```sh
❯ npm install --save chalk
```

###[Update-notifier](https://www.npmjs.com/package/update-notifier/tutorial)
Inform your package users of updates in a non-intrusive way.
```sh
❯ npm install update-notifier
```
###[yql](https://github.com/derek/node-yql)
node-yql is a YQL (Yahoo Query Language) client for node.js

```sh
❯ npm install yql
```