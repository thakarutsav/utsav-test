# Test Bank
This is created with Gulp, Gulp SASS and Browsersync. 

To run the code on a localhost, kindly use the `$gulp` command when in the project folder.

## Prerequisites of running the code on localhost are as below

`1.NodeJS
2.Gulp
3.Browser-sync`

## To install gulp,gulp-sass and browser-sync use the below command in your Node CLI

`npm install gulp gulp-sass browser-sync --save-dev`

The above command will update you package.json with dependencies in your dev environment.

## Folder Structure

I have tried to keep it simple with `src` files containing all the assets like `js,scss,images,css`
For SCSS there are two folder have Base SCSS and Module SCSS and `main.scss` imports all the modules for easy debugging or maintenance.
Global colors are defined in `variables.scss` partial.
