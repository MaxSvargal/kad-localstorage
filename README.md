kad-localstorage
================

[![Build Status](https://secure.travis-ci.org/omphalos/kad-localstorage.png)
](http://travis-ci.org/omphalos/kad-localstorage)
[![Coverage](https://coveralls.io/repos/omphalos/kad-localstorage/badge.svg)
](https://coveralls.io/github/omphalos/kad-localstorage)

An interface to localStorage for kad.

Installation
============

    npm install kad-localstorage

Usage
=====

    var kad = require('kad')
    var KadLocalStorage = require('kad-localStorage')

    var dht = kad({
      // ...
      storage: new KadLocalStorage('label')
    })

The `'label'` is used to namespace your data in localStorage.

License
=======

MIT