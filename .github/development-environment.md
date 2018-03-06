# Development environment

> references [ESLint](http://eslint.org/docs/developer-guide/development-environment)

This is a step-by-step guide to setting up a local development environment that will let you contribute back to the project.

## Install Node.js
Go to http://nodejs.org/ to download and install the latest stable version for your operating system.

Most of the installers come with npm already installed, but if for some reason it doesn’t work on your system, you can install it manually using the instructions on the website.

## Fork and checkout your own ESLint repository
Go to [TUI Github Repository][#TUI-Github-Repository] and click the “Fork” button. Follow the GitHub documentation for forking and cloning.

Once you’ve cloned the repository, run npm install to get all the necessary dependencies:

```sh
$ cd [tui-root-directory]
$ npm install
```

You must be connected to the Internet for this step to work. You’ll see a lot of utilities being downloaded.

## Add the upstream source
The upstream source is the main TUI repository that active development happens on. While you won’t have push access to upstream, you will have pull access, allowing you to pull in the latest code whenever you want.

To add the upstream source for TUI item, run the following in your repository:

```sh
$ git remote add origin [clone-link]
```

Now, the remote upstream points to the upstream source.


## Run the tests
Running the tests is the best way to ensure you have correctly set up your development environment. Make sure you’re in the eslint directory and run:

```sh
$ npm run test
```
The testing takes a few seconds to complete. If any tests fail, that likely means one or more parts of the environment setup didn’t complete correctly. The upstream tests always pass.

```sh
$ npm run lint
```
Runs just the JavaScript linting on the repository

## Workflow
Whenever you make changes to source files, you’ll need to run npm test to rerun the tests. The workflow is:

1. Make changes
2. Run npm test to run tests on the command line

You’ll have to do this each time you make a change. The tests are run automatically whenever a pull request is received, so make sure to verify your changes work before submitting them.
