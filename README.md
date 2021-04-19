# js-boilerplate

Framework-less boilerplate for a Javascript webapp.

## About

This is for my personal use&mdash;there's not much to it. The boilerplate consists of:

-   Basic project structure:
      -   **src** and **dist** directories
      -   Requisite **index.html**, **index.js**, and **styles.css** files
-   Basic NPM config
-   Basic Webpack config
-   Basic ESLint and Prettier config
-   NPM scripts to:
      -   Run Webpack commands
      -   Build and serve the Webpack bundle
-   A few Webpack loaders:
      -   style-loader
      -   css-loader
      -   file-loader
      -   babel-loader

I hope to keep the boilerplate updated as I continue to learn about useful tools in the JS ecosystem and adopt them into my workflow.

## To Use:

**_Note:_** These instructions are for the GitHub CLI client. For instructions on using the GitHub UI, see the [GitHub documentation](https://docs.github.com/en/free-pro-team@latest/github/creating-cloning-and-archiving-repositories/creating-a-repository-from-a-template).

1. Make sure you have the [GitHub CLI client installed and configured](https://github.com/cli/cli).

2. On your local machine, navigate to the parent directory where you want the directory for the new project to be created.

3. Create the new repo:
   `gh repo create <project name> --template https://github.com/daaf/js-boilerplate.git`.

4. From the project directory, pull from the remote repo on GitHub: `git pull origin master`.

5. Rename the project in **package.json** and **package-lock.json**.

6. Install dev dependencies:
   `npm install`.

7. Delete this readme :grin:.
