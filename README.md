# Blendwebmix VueJS poc

## Installation

 * clone the project
 * copy paste the js/api-key-dist.js to js/api-key.js and change the value of the api-key to your Marvel Api (register on http://developer.marvel.com)
 * npm install
 * npm run-script serve
 * open your browser with localhost:8080

## Description

This project is a quick demo of what can be done with VueJS, and how it can simplify your daily 
life web developer ;-)
There is no build stack like browserify or webpack because the aim is to focus on the mecanisms provided by VueJs.
This is also why js/css dependancies are hardly stored in the repository (/js, /css).

## TODO

* Use a Dependancy Injector to inject the HTTP service and add a Mock for this to be able to test it
* On another branch, use webpack to package dependencies into one bundle (vu and vue-resource plus materialize css and fonts file)
