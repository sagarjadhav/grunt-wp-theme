grunt-wp-theme
===
WordPress Starter Theme for use as a starting template for building custom themes. Uses Sass and AutoPrefixr, UglifyJS, and Grunt for all processing tasks.

Install Grunt
---------------

Grunt and Grunt plugins are both installed using <a href="https://npmjs.org/">npm</a>, the Node.js package manager. If you don’t have Node.js installed on your machine visit the <a href="http://nodejs.org/download/">download page</a> and grab the installer for your operating system. Follow the steps in the installation wizard and you should be up and running in no time. `npm` is included in the install.

Once you have `Node.js` and `npm` installed you can install the `grunt-cli` package.

`npm install -g grunt-cli`

The `-g` flag will install `grunt-cli` globally so you will only ever have to run this command once.

Install packages
---------------

I have created `package.json` file you can install all of the dependencies you specified using a single command:

`npm install`

This command will fetch all of the packages and store them in a new `node_modules` directory in your project route. You may want to add this directory to you `.gitignore` file (or similar) so that it doesn’t get checked in to version control.

Run Grunt
---------------

Executing the grunt command in your terminal will run all of the tasks specified in your default task.

You can also run tasks individually by passing the task name to the grunt command.

`grunt           // Runs default tasks`

`grunt compass   // Just runs the compass task`