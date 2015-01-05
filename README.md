# bower_components

The best project ever.

## Getting Started
### On the server
Install the module with: `npm install bower_components`

```javascript
var bower_components = require('bower_components');
bower_components.awesome(); // "awesome"
```

### In the browser
Download the [production version][min] or the [development version][max].

[min]: https://raw.github.com/awhiting/bower_test/master/dist/bower_components.min.js
[max]: https://raw.github.com/awhiting/bower_test/master/dist/bower_components.js

In your web page:

```html
<script src="dist/bower_components.min.js"></script>
<script>
awesome(); // "awesome"
</script>
```

In your code, you can attach bower_components's methods to any object.

```html
<script>
var exports = Bocoup.utils;
</script>
<script src="dist/bower_components.min.js"></script>
<script>
Bocoup.utils.awesome(); // "awesome"
</script>
```

## Documentation
_(Coming soon)_

## Examples
_(Coming soon)_

## Contributing
In lieu of a formal styleguide, take care to maintain the existing coding style. Add unit tests for any new or changed functionality. Lint and test your code using [Grunt](http://gruntjs.com/).

_Also, please don't edit files in the "dist" subdirectory as they are generated via Grunt. You'll find source code in the "lib" subdirectory!_

## Release History
_(Nothing yet)_

## License
Copyright (c) 2015 Ashley Whiting  
Licensed under the MIT license.
