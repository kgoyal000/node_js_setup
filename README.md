# node_js_setup
Basic Node Js Setup. 

# STEPS To Run project using node js

1. Install Node.js for your platform (MacOS, Windows or Linux)

2. Open a command prompt and type:
    mkdir myapp
    cd myapp
    
3. Initialize your project and link it to npm
    npm init
    (This will create package.json file in your folder)
    
4. Install Express in the myapp directory
    npm install express --save
    
5. Start your text editor of choice and create a file named app.js.
    Write the following:
    var express = require('express');
    var app = express();
    app.get('/', function (req, res) {
      res.send('Hello World!');
    });
    app.listen(3000, function () {
      console.log('Example app listening on port 3000!');
    });
    
 6. Run the app
    node app.js
