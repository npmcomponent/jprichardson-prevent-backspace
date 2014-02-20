*This repository is a mirror of the [component](http://component.io) module [jprichardson/prevent-backspace](http://github.com/jprichardson/prevent-backspace). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/jprichardson-prevent-backspace`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
prevent-backspace
================

Is a client-side JavaScript component that prevents the backspace from navigating back in the browser.

You can use it with [browserify](https://github.com/substack/node-browserify) or [component](https://github.com/component/component).



Browserify
----------

    npm install prevent-backspace


Component
---------

    component install jprichardson/prevent-backspace



Example
------


```javascript
var preventBackspace = require('prevent-backspace')
preventBackspace() //hitting `backspace` outside of input, select, or textarea will be swallowed
```


Credits
-------

This originated from this question: http://stackoverflow.com/questions/1495219/how-can-i-prevent-the-backspace-key-from-navigating-back. I repackaged [this answer](http://stackoverflow.com/a/8218367/10333) and removed jQuery dependence.



License
-------

(MIT License)

Copyright 2013, JP Richardson  <jprichardson@gmail.com>


