mutant.js
=========

a system for node.js and express that unifies client and server page rendering in an SEO-friendly way

INSTALLATION
============

    npm install mutant

USAGE
=====

    var mutant = require('mutant');
    var mw     = require('mutant/middleware');

DEV
===

    coffee --watch --compile *.coffee &
    lsc    --watch --compile *.ls     &

TODO
====

- extract more code from weedmaps-node project
- port coffeescript code to livescript
- write package.json for lib 
- write example app
- write documentation
