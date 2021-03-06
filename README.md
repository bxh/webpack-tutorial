## Overview

A reference Webpack configuration

## Clone This Repository

1. ```git clone git@github.com:vp-online-courses/webpack-tutorial.git```
1. ```cd webpack-tutorial```

## Branches

This repository consists of many branches, which correspond to different lessons of the course.
Every lesson that requires code changes has 2 branches associated with it:

1. First branch points to the beginning of the lesson.
1. Second branch points to the end of the lesson.

Let's take as an example *"Minification Of The Resulting JavaScript Bundles"* lesson.
There are 2 branches associated with it:
1. *minification-of-the-resulting-javascript-bundles-begin*. You can check out this branch right before starting the lesson and repeat all the steps from the lesson while watching it.
2. *minification-of-the-resulting-javascript-bundles-end*. If you want to see how the application looks like at the end of this lesson, you can check out this branch.

Don't forget to run ```npm install``` when switching branches.
- ```git checkout minification-of-the-resulting-javascript-bundles-begin```
- ```npm install```

There are 2 special branches that you may want to check out:
- single-page-application. Contains webpack configuration for a Single Page Application.
- multiple-page-application. Contains webpack configuration for a Multiple Page Application.

## Single Page Application

#### Run in Development Mode

1. ```git checkout single-page-application```
1. ```npm run dev```

Application will be served on the ```http://localhost:9000/```.

#### Run in Production Mode

1. ```git checkout single-page-application```
1. ```npm run build```
1. ```npm start```

Application will be served on the ```http://localhost:3000/```.

## Multiple Page Application

#### Run in Development Mode

1. ```git checkout multiple-page-application```
1. ```npm run dev```

Application will be served on the ```http://localhost:9000/```.
It will show an empty page.

In order to go to the "Hello World" page, go to ```http://localhost:9000/hello-world.html```.

In order to go to the "Kiwi" page, go to ```http://localhost:9000/kiwi.html```.


#### Run in Production Mode

1. ```git checkout multiple-page-application```
1. ```npm run build```
1. ```npm start```

Application will be served on the ```http://localhost:3000/```.
It will show an empty page.

In order to go to the "Hello World" page, go to ```http://localhost:3000/hello-world```.

In order to go to the "Kiwi" page, go to ```http://localhost:3000/kiwi```.
