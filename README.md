# Reading List

This project is an exercise in building a simple single page application using AngularJS.
There is a CodeSchool video that allows you to build this app by coding along with the tutorial. 
You can use the application to build a reading list containing book title, author, review, and genres.  The ISBN-10 serves up the book cover.


## Getting Started

To get you started you can simply clone the repository and install the dependencies:


### Prerequisites

You need git to clone the repository. You can get git from [http://git-scm.com/](http://git-scm.com/).

I also use a number of node.js tools to initialize. You must have node.js and its package manager (npm) installed.  You can get them from [http://nodejs.org/](http://nodejs.org/).


### Clone ReadingList
Clone the angular-seed repository using [git][git]:

```
git clone https://github.com/timhyson/ReadingList.git
cd ReadingList
```


### Run the Application

The project is preconfigured to run with a simple development web server.  The simplest way to start this server is:

```
npm start
```

Now browse to the app at `http://localhost:8000/app/index.html`.


## Directory Layout

```
app/                    --> all of the source files for the application
  bower_components/     --> all app specific modules
  css/                  --> stylesheets
  index.html            --> app layout file (the main html template file of the app)
  js/
    app.js              --> main application module
  partials/
    app.html            --> element of main application module
    book-cover.html     --> element of main application module
    book-genres.html    --> element of main application module
    review-form.html    --> element of main application module
  bower.json

```


## Contact

For more information on the AngularJS components used in this application please check out http://angularjs.org/

[codeschool] (https://www.codeschool.com/screencasts/soup-to-bits-shaping-up-with-angular-js)

[git] (http://git-scm.com/)

[bower] (http://bower.io)

[npm] (https://www.npmjs.org/)

[node] (http://nodejs.org)

[protractor] (https://github.com/angular/protractor)

[jasmine] (http://jasmine.github.io)

[karma] (http://karma-runner.github.io)

[travis] (https://travis-ci.org/)

[http-server] (https://github.com/nodeapps/http-server)
