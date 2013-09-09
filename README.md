fileManager
===========

A library that helps with storing files, retrieving, removing files using the FileSystem API

Background
========
Developed for use in [Enketo Smart Paper](https://enketo.org), but without external dependencies. It can be used in any situation requiring persistent folder-based file storage inside a browser.

Features
=====
* persistent storage of files in folders with a unique ID
* lightweight - only includes features that are required for enketo


Prerequisites
=====
* jQuery

Future
======
* Sample usage page
* Automated testing on Travis (with node.js webserver?)
* Would like to refactor this and use a workflow that emits events to more elegantly deal with all the chained asynchronous function calls
