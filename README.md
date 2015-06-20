karma-grooscript
==========

An grooscript plugin for karma.

[Grooscript](http://grooscript.org/) for [Karma](http://karma-runner.github.io)

Installation
------------

From Github:

```sh
$ npm install 'git+https://github.com/antoaravinth/karma-grooscript.git' --save-dev
```

Once installed, you can need refer the plugin in the karma config:

```
module.exports = function(config) {
  config.set({
  
    . . . 

    frameworks: ["grooscript"]

    . . . 
})
```

Usage
------

Once the plugin is loaded by the karma, `gs` is avialble on the karma test runners.

License
-------

The MIT License (MIT)