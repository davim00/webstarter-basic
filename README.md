<h1 align="center">
  Basic Web Starter
</h1>

<h4 align="center">
  Web Development Using HTML, jQuery, SCSS, Bootstrap, and Grunt
</h4>

<p align="center">
  <img src="https://img.shields.io/badge/HTML-5-E54C20"> <img src="https://img.shields.io/badge/jQuery-3.5.1-0A69AD"> <img src="https://img.shields.io/badge/SCSS-1.26.12-CE649A"> <img src="https://img.shields.io/badge/Bootstrap-4.5-7952B3"> <img src="https://img.shields.io/badge/Grunt-1.0.4-E48532">
</p>

## Features

- Uses [Bootstrap 4.5](https://getbootstrap.com) SCSS implementation for modular customization of styles
- [Grunt](https://gruntjs.com/) watch task automates Sass compilation, JS compilation, and live reload upon the saving of any JS, SCSS, or HTML file
- Uses [NPM](https://www.npmjs.com/) to install task and build packages
- Gruntfile.js includes optional tasks for image minification and distribution building

## Installation

1. Download or clone the project into a working directory on your local machine.
2. Rename the project Directory to the name of your project.
2. Open a terminal (MacOS, Linux) or Bash shell (Windows Subsystem for Linux) and `cd` to your project directory.
3. Run `npm install` in the project directory to download and install NPM packages and dependencies ([node.js](https://nodejs.org/en/) must be installed on the local machine in order to use `npm`).
4. [Install Grunt](https://gruntjs.com/getting-started) if it hasn't been installed already.

## Usage

Since this is a project for starting other projects, it is recommended to rename the project directory to the name of your local project. Once installation is complete, you can begin your project in the index.html file, using Bootstrap compatible markup.

If you would like to customize the Bootstrap CSS, you may do so in the files in the SASS directory. Add and remove SCSS files in styles.scss. If changes need to be made to core Bootstrap files, it is recommended to copy those files into the SASS directory and change the reference path in styles.scss. See [Theming Bootstrap](https://getbootstrap.com/docs/4.5/getting-started/theming/) for more information on customization.

Run `grunt watch` to start the task watching files and folders for changes. The `watch` task will update CSS and Javascript files with each change. It also includes the LiveReload server that can be used in Chrome with the [LiveReload extension](https://chrome.google.com/webstore/detail/livereload/jnihajbhpnppcggbcgedagnkighmdlei) to enable auto-reload of HTML pages when file changes are saved. The `watch` task is stopped by pressing ctl+c on the keyboard.
