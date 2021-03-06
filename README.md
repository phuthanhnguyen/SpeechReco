# Angular/Express Skel

Initially based on [Angular Express Seed](https://github.com/btford/angular-express-seed).

With Bower and Grunt.

## How to use it

1. clone the repository (or fork to hack it!)

        git clone https://github.com/th0masm/angular-express-skel.git

2. install node.js

3. install the npm dependencies

        npm install -g grunt-cli bower

4. install the gjslint dependency

        easy_install http://closure-linter.googlecode.com/files/closure_linter-latest.tar.gz

    more informations [can be found here](https://developers.google.com/closure/utilities/docs/linter_howto)

5. Go into the project directory and install project dependencies

        cd angular-express-skel
        npm install
        bower install

6. Launch it

        grunt dev

### Grunt

    grunt
    grunt linters
    grunt dev

## Directory Layout
    
    app.js              --> app config
    package.json        --> for npm
    bower.json          --> for bower
    Gruntfile.js        --> tasks for linter and dev
    .bowerrc            --> config file for bower
    frontend/           --> all of the files to be used in on the client side
      css/              --> css files
        app.css         --> default stylesheet
      js/               --> javascript files
        app.js          --> declare top-level app module
        controllers.js  --> application controllers
        directives.js   --> custom angular directives
        filters.js      --> custom angular filters
        services.js     --> custom angular services
      views/
        index.jade        --> main page for app
        footer.jade       --> footer for app
        layout.jade       --> doctype, title, head boilerplate
          partials/         --> angular view partials (partial jade templates)
           partial1.jade
           partial2.jade
    backend/
      api.js            --> route for serving JSON
      index.js          --> route for serving HTML pages and partials
      
## Next steps 

Yeoman generator.

## Contributors

- You!

## License

(The MIT License)

Copyright (c) 2014 Th0masm

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the 'Software'), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
