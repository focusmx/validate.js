This is a fork of ansman/validate.js since it no longer appears to be maintained.
The documentation will be updated to reflect the change in name.

validate.js
===
Validate.js provides a declarative way of validating javascript objects.

For documentation please see [validatejs.org/](http://validatejs.org/).

For issues and feature requests visit the [issue tracker](https://github.com/focusmx/validate.js/issues).

Building validate.js
---
### Requirements
  * [node.js](https://nodejs.org/) - Will probably work with most versions
  * [grunt-cli](http://gruntjs.com/using-the-cli)

### Build steps
  1. `git clone git@github.com:ansman/validate.js.git`
  2. `cd validate.js`
  3. `npm install`
  4. `grunt build`

This will build *validate.min.js*, *validate.min.map* and the *docs* folder.

### Continuous testing
You can run continuous testing that runs the tests on file changes by running
`grunt watch` or simply `grunt`.

If you want to just run the tests once you can do that by running `grunt test`.

Build status
---


Contributing
---
Before opening a pull request please make sure your changes follow the
[contribution guidelines](https://github.com/focusmx/validate.js/blob/master/CONTRIBUTING.md).

Users of validate.js
---
If your site, library or application uses validate.js and would like to be shown
here please feel free to 
with the name and optionally a URL to the project and it will be added here.
