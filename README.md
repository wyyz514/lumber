# Lumber

Converts a DOM tree to an object

## Usage
```js
import Lumber from '/path/to/Lumber';

const parsed = Lumber.parse(`[HTML template]`);
```

## Issues
Yes. WIP but will work for basic HTML elements with attributes etc. 
Exception occurs with attribute values that have not been adequately considered ie JSON strings and special symbols. 

- HTML attribute considerations: looser regular expression required?
- Whitespace between element nodes breaks parser...needs experimentation...replace >\s< with >< ?
