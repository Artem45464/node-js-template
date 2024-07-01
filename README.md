# node-js-template

A barebones Node.js app using 
<a href="http://expressjs.com/" rel="nofollow">Express 4</a>

This application supports the  <a href="https://devcenter.heroku.com/articles/getting-started-with-nodejs" rel="nofollow">Getting Started with Node on Heroku</a>  the article  - check it out.

# Running Locally
<p dir="auto">Make sure you have <a href="http://nodejs.org/" rel="nofollow">Node.js</a> and the <a href="https://cli.heroku.com/" rel="nofollow">Heroku CLI</a> installed.</p>

    $ git clone git@github.com:jomaoppa/node-js-template.git  # or clone your own fork
    $ cd node-js-template
    $ npm install 
    $ npm start


Your app should now be running on  <a href="http://localhost:5000/" rel="nofollow">localhost:5000</a>


Deploying to Heroku 

    $ heroku create
    $ git push heroku master  
    $ heroku open

