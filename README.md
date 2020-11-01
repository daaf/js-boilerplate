# js-boilerplate
Super basic boilerplate for a Javascript webapp.

## About
This is for my personal use, and I'm a beginner, so there's not much to it. For now, it contains:
- Basic project structure: **src** and **dist** directories, requisite **index.html**, **index.js**, and **styles.css** files
- Basic NPM config
- Basic Webpack config
- A few NPM scripts to build and serve the Webpack bundle
- A few Webpack loaders:  style-loader, css-loader, file-loader, babel-loader

I hope to keep the boilerplate updated as I continue to learn about more useful tools and adopt them into my workflow.

## To Use:
***Note:*** These instructions are for the GitHub CLI client. For instructions on using the GitHub UI, see the [GitHub documentation](https://docs.github.com/en/free-pro-team@latest/github/creating-cloning-and-archiving-repositories/creating-a-repository-from-a-template).
1. Make sure you have the [GitHub CLI client installed and configured](https://github.com/cli/cli).

2. On your local machine, navigate to the parent directory where you want the directory for the new project to be created.

3. Create the new repo:
 `gh repo create <project name> --template https://github.com/daaf/js-boilerplate.git`.
 
4. Rename the project in **package.json** and **package-lock.json**.

5. Install dev dependencies:
 `npm install`.
 
 6. Delete this readme :grin:
