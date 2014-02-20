*This repository is a mirror of the [component](http://component.io) module [component/transitionend-property](http://github.com/component/transitionend-property). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/component-transitionend-property`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# transitionend-property

  get the browser-specific transitionend property

## Installation

    $ component install component/transitionend-property

## Example

```js
var transitionend = require('transitionend-property');
el.addEventListener(transitionend, fn);
```

## API

  Exports the name of transform property as a `String` or `null` if the property is not supported.

## License

  MIT
