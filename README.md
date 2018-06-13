Glozzom is a multi-page website theme aimed at selling a membership
service or something of that nature.

It makes use of Bootstrap 4.1.1, Font Awesome, jQuery, Lightbox and popper.js

Image files  and /node_modules have been ignored to save storage space and
sync efficiency. They are just place holder images anyway. So you aren't really
missing out on much there.

This project was part of the course content for
https://www.udemy.com/bootstrap-4-from-scratch-with-5-projects


## Commands to create workflow. Below text can be copy/pasted into a .sh file
## if you feel the need to automate.
## ============================

#!/bin/bash

$ mkdir {directory_name}
$ cd directory_name
$ npm init
$ atom .      ## this is not needed but helps open the package.json file
              ## for editing and monitoring during following steps.
$ npm install boostrap@4.1.1 font-awesome jquery popper.js --save
$ npm install gulp gulp-sass browser-sync --save-dev

## Uncomment the next line only if gulp is not already installed globally
## $ sudo npm install -g gulp-cli



## ==================================
## Once this has been done you can run gulp and it will
## execute all the commands in gulpfile.js and compile and
## move all the appropriate css and js files.
## Then all that remains to do is delete the node-modules directory
## and anything else leaving only
## /src
## gulpfile.js
## package.json

## which is all the files you need to start a new project
## Copy/Paste those files into a new project folder to begin.

## Finally once pasted into project folder run
$ npm install
$ npm start
