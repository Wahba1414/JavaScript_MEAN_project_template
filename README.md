# Project Title
JavaScript MEAN stack project template 


## Description 
Template for JavaScript MEAN stack project contains all needed structure setup and ready to download and start implementing your porject quickly.

### Contents

```
Project
│   README.md       --> Contains project description you are reading now.
│   Gruntfile .js   --> Contains Grunt "Tasks Runner"  configurations with some plugins as examples "develop, watch and jshint".
│   package.json    --> Contains all npm packages needed for this project.
|   bower.json      --> Contains all bower packages needed for this project. 
|   
└─── server --> Folder contains all Back-End codes.
│   │   
│   └─── express --> Folder contains "Express" configurations and "routes" files for app APIs.
|        |
|        |_____ configs.js  --> File contains all needed "Express" configurations like its middlewares and so on.
|        |
|        |_____ routes      --> Folder contains all routes for this app APIs.
|           
│       
│   │   
│   └─── models  -->  Folder contains all Mongoose models and its plugins.
│          
│       
│   │   
│   └─── controllers --> Folder contains all modules which handle different APIs.
│          
│       
│   │   
│   └─── utilis   --> General utilis which needed by different app's modules.
│          
│       
│   │   
│   └─── app.js   --> App startup script to set the needed configurations, load Mongoose models, start listening and so on. 
|
│          
│       
│   
└─── client  --> Folder contains all "Front-End" codes.
    │   
    └─── configs  --> Folder contains all configurations needed for Angular.js main app module.
         |
         |_____ app_setup.js  --> Create Angular.js main Module and setup its dependancies.
         |
         |_____ routes        --> Contains all "Front-End" routes/states.
           
       
    │   
    └─── controllers --> Folder contains all Angular.js controllers.
          
       
    │   
    └─── services    --> Folder contains all Angular.js services.
          
       
    │   
    └─── views       --> Folder contains all views and HTML files.
          
       
    │   
    └─── styles      --> Folder contains all custom styles CSS files.

    |
    └─── images      --> Folder contains all app images.
          
       
    │   
    └─── index.html  --> the main index file includes all "Front-End" codes.
           
```


### Prerequisites
* Know about JavaScript MEAN stack.
* Have npm & bower installed on your machine.

### Building Steps:

* Download project source code.

* Build the needed NPM modules as following
    ```
    npm install
    ```

* Build the needed bower modules as following
    ```
    bower install
    ```

* Run this app as following.
    ```
    grunt
    ```
    runs default Grunt tasks for you (running Node.js app, watch for any changes). And also there is a separate task can use to lint your JavaScript codes "jshint" as following.
        ```
        grunt jshint
        ```

* From browser just type 
    ```
    http://localhost:8080/
    ```






 