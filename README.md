# HTML-Starter-Kit
_Made by Luciano Nooijen_
Version 1.0.0 (still in development)

[![Build Status](https://travis-ci.org/AllStarterKits/HTML-Starter-Kit.svg?branch=master)](https://travis-ci.org/AllStarterKits/HTML-Starter-Kit) 
[![Dependency Status](https://david-dm.org/lucianonooijen/AllStarterKits.svg)](https://david-dm.org/AllStarterKits/HTML-Starter-Kit)
[![devDependency Status](
https://david-dm.org/AllStarterKits/HTML-Starter-Kit/dev-status.svg)](https://david-dm.org/AllStarterKits/HTML-Starter-Kit#info=devDependencies)

## Why this starter kit?
For many custom html/css/js websites I make I have to do the same thing over and over again. To make it a bit easier for myself I made this starter kit with the tools I love to use. For this reason I integrated handlebars for templating (partials, yaay) and made it so that everything can be put in the src folder (and views for templating). Feel free to use this starter kit or edit it to your own preferences.

## Installation
This Starter Kit requires [Node.js](https://nodejs.org/) to run.
```sh
$ npm install
```
```sh
$ gulp
```

## Useful notes
Just a handful of useful notes I would recommend using when you work with this starter kit.
* Don't add any files into the ./dist folder. Always put them in the ./src folder. All images and such will be copied so don't worry. (And otherwise you can always change the gulpfile.js to include the stuff you added if it's not there yet)
* This starter kit is not meant to be used as a NodeJS server during production, but rather as a development enviroment that will give you the files you can upload to your server (all of the stuff from the ./dist folder). If you are looking for a NodeJS Starter Kit, you can take a look at [my NodeJS Starter Kit](https://github.com/lucianonooijen/NodeJS-Starter-Kit).

## Contributors
[lucianonooijen](https://github.com/lucianonooijen/)

## Licence
MIT - so use it whenever, where-ever and however you want it :)
