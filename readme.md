# grunt-example-site

## Node.js example page to facilitate a Grunt tutorial.

Install this example using Git (requires Node/NPM and Git to be installed):

* `git clone https://github.com/tholf/grunt-example-site.git`
* `cd grunt-example-site`
* `npm install`

At this point the Grunt example site is installed. To continue, we must ensure SASS compiler is installed and ready to use. Execute `sass --version` from a command prompt. A version will be display if a SASS compiler is installed. If not, see the "Install SASS for Complete Functionality" instructions below.

If you have SASS installed, execute `grunt build` at your command prompt. This will tell Grunt to build all the resources. 

Next we'll execute `grunt watch` and Grunt will now enter into a watch. In watch mode, Grunt will watch for file changes specified in the `gruntfile.js`file. If a change in a watched file is detected Grunt will perform the associated action and automatically reload the web page.

Then launch the `index.html` file in your browser. Now, when you change each of the HTML, CoffeeScript, or SASS files, they will automatically be recompiled and the web page reloaded.

> Neat huh?

------------------------

## Install SASS for Complete Functionality

For the complete functionality of this example, [SASS](http://sass-lang.com/install) must be installed. Installing the SASS compiler can be accomplished in many ways. Visit [sass-lang.com](http://sass-lang.com/install) for more info. 

Otherwise, simply choose only ONE of the following installations.


#### Install SASS through NPM package manager

The easiest is to install through the [npm](https://www.npmjs.com/) package manager since we are already using it with this example.

`npm install -g sass`


#### Install Anywhere as Standalone Executable

You can install Sass on Windows, Mac, or Linux by downloading the package for your operating system from [GitHub](https://github.com/sass/dart-sass/releases/) and [adding it to your PATH](https://katiek2.github.io/path-doc/). That's all—there are no external dependencies and nothing else you need to install.


#### Install Ruby and the SASS Ruby Gem

Most notably, SASS was originally developed to be compiled using Ruby. Visit [ruby-lang.org](http://www.ruby-lang.org/en/downloads/) to install Ruby. If you're on OS X or Linux you probably already have Ruby installed; test with `ruby -v` in your terminal. When you've confirmed you have Ruby installed, run `gem install sass` to install Sass.

-------------------------

Original credits: https://semaphoreci.com/community/tutorials/getting-started-with-grunt-js
