# Lumber

Converts a DOM tree to an object

## Usage
```js
import Lumber from '/path/to/Lumber';

const parsed = Lumber.parse(`[HTML template]`);
```

## Issues
Yes. WIP

- HTML attribute considerations: looser regular expression required?
- Whitespace between element nodes breaks parser...needs experimentation...replace >\s< with >< ?
