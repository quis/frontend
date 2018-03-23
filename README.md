# front-end library playground

A front-end library playground to test ideas and implementations.

## Prerequisites

Install git to clone the repo, instructions: https://git-scm.com/book/en/v2/Getting-Started-Installing-Git

You need to have Node.js (Node) installed onto your computer before you can install Gulp.

If you do not have Node installed already, you can get it by <a href="https://nodejs.org/">downloading the package installer from Node's website</a>.

When you're done with installing Node, you can install Gulp by using the following command in the command line:

`npm install gulp -g`

## Installation

Clone the repo: `git clone https://github.com/AdamChrimes/frontend-library.git` and whilst in the project directory, install the required npm packages with: `npm install`

## Usage

Start the server in development mode: `gulp`

View the site in a browser: `open http://localhost:3000`

## Deploying

https://nhs-uk-redesign.herokuapp.com/index.html

`git subtree push --prefix dist heroku master`

Automatic deployments coming soon.

## Decisions

- We use the Bootstrap 3 grid system due to the popularity of the framework and support for earlier version of IE8.
