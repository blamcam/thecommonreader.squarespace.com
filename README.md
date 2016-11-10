# myronrodrigues.com

> Jekyll theme for myronrodrigues.com

This theme for Jekyll uses __Jekyllized__ as detailed below in a similar way to [LittleBooks](littlebooks.github.io)

## Introduction

`generator-jekyllized`[https://github.com/sondr3/generator-jekyllized] is a very opinionated [Yeoman][yeoman] generator built with [Jekyll][jekyll] and [gulp][gulp].

## Installation

### Node.js
In the site folder, switch over to the latest node.
```
$ nvm use 5.9.1
```
### Install Dependancies
NOTE: these dependancies get installed to the 5.9.1 node and hence will be utilised every time you "use" the version of Node via NVM.
* **Ruby**: `>2.0` with Bundler `>1.10`
* **Node**: `>4.2`, Gulp `>4.0` and Yo `>1.7.0`
* **Gulp:** Since the beta is running Gulp 4.0 you need to install `gulp-cli`:
  `npm install gulpjs/gulp-cli#4.0 -g`
* **Jekyllized:** Then install Jekyllized: `npm install
  generator-jekyllized@next -g`

### Configure Yeoman
In the __installation folder__
```
$ yo jekyllized
```
## To get started

```
$ gulp [--prod]
```
And you'll have a new Jekyll site generated for you and displayed in your
browser. Neato. If you want to run it with production settings, just add
`--prod`.

Clean and rebuild during testing...
```
$ gulp clean
$ gulp rebuild
```

## Committing and deploying

### Github
NOTE: You may have to add the ssh key before SSHing into Github

```
$ ssh-add ~/.ssh/gh_rsa
```
This repository is synchronised to the remote repo https://github.com/myronrodrigues/myronrodrigues.com.git

```
$ git add .
$ git commit -m "removed forced HTTPS"
$ git push origin master
```
### Amazon AWS
```
$ gulp deploy
```
This will use [`gulp-awspublish`][awspublish] and the AWS credentials in the aws-credentials.json file.

## Owner

> [Myron Rodrigues](myronrodrigues.com)
