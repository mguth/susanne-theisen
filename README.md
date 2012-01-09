Susanne Theisen
==========================

In this repository you’ll find the Middleman project for susanne-theisen.de. The files consist of Haml for markup, Sass for styling and JavaScript for interaction.

Install
-------

If you have RVM installed, installation should be automatic the first time you change into this project directory (using `cd`). If this does not work you can setup the project manually with **4 Steps**:

    rvm 1.9.2
    rvm gemset create susanne-theisen
    gem install bundler
    bundle install

Running
-------

### Building static pages

You can build the site into a `build`-directory:

    middleman build

The `build` directory will contain the generated HTML, CSS and JavaScript and the contents can be uploaded to any standard web server.

### With the built-in server

To run:

    middleman server

You will see the generated HTML & CSS by navigating to <http://localhost:4567/>.