Per the Webpack documentation

> When a single loader is applied to the resource, the loader is called with only one parameter -- a string containing the content of the resource file.

This is the exact signature of the `extract` function in [mjstahl/lavascript/extract.js.md](https://github.com/mjstahl/lavascript/blob/master/extract.js.md).

So let's just export the function and call it a day.

    module.exports = require('lavascript')
