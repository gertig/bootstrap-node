**Fun fact: due to this project I owned the `bootstrap` npm package name before Twitter bootstrap came on the scene. I tried for a couple of years to give them the name and was finally able to do so!**

`bootstrap` allowed you to create a new node.js app with a few things already setup to get you started. It takes a lot of inspiration from the express app executable.

You can use Javascript or Coffeescript by following the prompts.

## Usage

    $ npm install -g bootstrap
    $ bootstrap yourappname
    $ cd yourappname
    $ npm install

If you are using Heroku's Cedar stack and Foreman you can now do

    $ foreman start

If you want to start it with node you can do

    $ node app.js

If you are using CoffeeScript then you can do

    $ coffee app.coffee

TODO:

* Add support for .scss
* Add support for Mustache and Icanhaz.js templates
