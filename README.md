# loopback-angular-ui-router

## Overview

loopback-angular-ui-router is a starter pack for creating websites hosting a LoopBack REST API presented using an AngularJS and Bootstrap (CSS) frontend. It aims to scaffold the construction of a full-stack website and aid the developer by offering a simple user experience to do that. All the hard stuff is already taken care of for you by a toolchain of robust, popular and conceptually similar libraries and tools.

## Features

### Bootstrap, Angular and UI Router responsive frontend

Take advantage of [AngularJS](https://angularjs.org/) 1.4.0, one of the most popular JavaScript SPA frameworks out there. Use two-way data-binding, heirarchical routing, and the excellent REST API interface provided by this module to create a great user experience. 

Bootstrap CSS gives you a familiar toolkit to begin laying our your site, and you don't have to know SASS to work with it. Want to include Bootstrap's JS features? 

```npm install --save jquery``` 

and add the jQuery and Bootstrap JS scripts into index.html. Want to replace bootstrap all together? 

```npm uninstall --save bootstrap``` 

then remove the script tag from index.html. Use whatever tools suit you best, without a fight.

Includes [html5-boilerplate](https://github.com/h5bp/html5-boilerplate) and [es5-shim](https://github.com/es-shims/es5-shim) to polyfill older browsers' JS features while building toward web standards. Apply further polyfill as necessary.

### [Grunt](http://gruntjs.com/) build process

Keep your production website's footprint small without a ton of work by letting build automation do that for you. The ```grunt``` command line build tool makes development, testing, and preparation for deployment all fairly straightforward.

The AngularJS frontend was generated by Yeoman using [generator-angular-ui-router](https://github.com/iamblue/generator-angular-ui-router), which provides an easy-to-use by extremely mature build process that runs jshint and karma/jasmine tests each time ```grunt``` is called. It concatenates, minifies, and respects the script include order as defined in index.html.

```grunt``` is widely accepted, written with CommonJS and has a huge task ecosystem. There are many package managers, but this one is here to stay, so stop worrying about your build tool becoming obselete and just do something for once!

### Use Strongloop Arc and command line generators 

run ```slc arc``` to launch [Strongloop Arc](http://docs.strongloop.com/display/APIS/Using+Arc) -- a GUI editor for your LoopBack model relationships, datasources, middleware and REST API. Building an API has never been simpler.

Use ```slc loopback:<command>``` at the command line to create LoopBack models, datasources, boot-scripts and more. Read the [slc loopback manual](http://docs.strongloop.com/pages/releaseview.action?pageId=3836281).

Use ```yo angular:<command>``` at the command line to create AngularJS views, controllers, services and more. Read the [yo angular manual](https://github.com/yeoman/generator-angular).

### Automates REST API glue code

Automatically generate injectable services in AngularJS for any model exposed by the LoopBack REST API each time you run ```grunt```. The task manager runs [grunt-loopback-sdk-angular](https://github.com/strongloop/grunt-loopback-sdk-angular) to update a set of ngResource services from the REST API configuration in LoopBack so you don't have to.

## Why isn't this a Yeoman generator?

Good question. I really ought to get on that.

## Contrbutors

Jeff Rose, @DigiMachinist

## Copyright and License

Code and documentation copyright 2015 Jeff Rose. Code released under the MIT license. Docs released under Creative Commons.