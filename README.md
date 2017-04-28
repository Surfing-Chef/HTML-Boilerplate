# HTML5 Boilerplate - High Test
> [HTML5 Boilerplate](https://html5boilerplate.com) has a ready to install task
manager and Bourbon, Bitters, and Neat at your disposal.  

### Task manager
> Manages most tasks like auto refresh, minify and source mapping.

INSTALLATION    

1. Your machine must have Node.js and NPM installed to use the task manager.  It is also assumed that you have WAMP or similar installed.  Find instructions [here](https://www.npmjs.com/get-npm?utm_source=house&utm_medium=homepage&utm_campaign=free%20orgs&utm_term=Install%20npm).  
2. Ensure the ***HTML-Boilerplate*** folder and all of its contents are copied into the ***www*** folder within the WAMP directory.  Or cloned to same directory from [github](https://github.com/Surfing-Chef/HTML-Boilerplate).   
3. To install the package.json and its dependencies, type `npm install`.  It may take a few minutes to install.

USING GULP - TASK MANAGER
1. To run the task manager: While in the root directory (containing *gulpfile.js*), type `gulp`.  
  - If your browser displays a **"Not Found"** error, open ***gulpfile.js*** and ensure the path around `line 56` points to ***HTML-Boilerplate*** on your machine.
2. To exit the gulp task manager while running, press **CTRL-C** twice.
3. To create a ***build*** folder for deployment, navigate the console to the root directory of the project folder (containing *gulpfile.js*). Type `gulp build`. It may take a while, especially if the project contains many images.  The new build folder should contain all the files necessary for a site to function when deployed to a server. 

* Note that sometimes Chrome is buggy with browserSync.  [This link](http://stackoverflow.com/questions/43068258/browsersync-gulp-version-injecting-new-css-changes-but-then-reloads-a-cached-c) helped.
