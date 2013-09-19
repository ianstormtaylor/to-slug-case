# to-slug-case

  Convert a non-slug-case string to a slug-case string.

## Installation

    $ component install ianstormtaylor/to-slug-case

## Example

```js
var slug = require('to-slug-case');

slug('camelCase');  // "camel-case"
slug('space case'); // "snake-case"
slug('dot.case');   // "dot-case"
slug('weird[case'); // "weird-case"
```

## API

### toSlugCase(string)
  
  Returns the slug-case variant of a `string`.

## License

  MIT