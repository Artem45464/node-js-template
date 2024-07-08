# node-js-template

A barebones Node.js app using 
<a href="http://expressjs.com/" rel="nofollow">Express 4</a>

This application supports the  <a href="https://devcenter.heroku.com/articles/getting-started-with-nodejs" rel="nofollow">Getting Started with Node on Heroku</a>  the article  - check it out.

# Running Locally
<p dir="auto">Make sure you have <a href="http://nodejs.org/" rel="nofollow">Node.js</a> and the <a href="https://cli.heroku.com/" rel="nofollow">Heroku CLI</a> installed.</p>

 ```bash
  $ git clone git@github.com:Artem45464/node-js-template.git # or clone your own fork 
  $ cd node-js-template
  $ npm install
  $ npm start
   ```


Your app should now be running on  <a href="http://localhost:5000/" rel="nofollow">localhost:5000</a>


# Deploying to Heroku 

   ```bash
    $ heroku create
    $ git push heroku master  
    $ heroku open
   ```
  
 
   or 
    
<a href="https://www.heroku.com/home" rel="nofollow">
    <img src="https://camo.githubusercontent.com/a45640b9f85b4daa9a7c8b106e324e58d2114cccd227df20185a04d931411701/68747470733a2f2f7777772e6865726f6b7563646e2e636f6d2f6465706c6f792f627574746f6e2e706e67" alt="Deploy to Heroku" data-canonical-src="https://www.herokucdn.com/deploy/button.png" style="max-width: 100%;">
</a>
