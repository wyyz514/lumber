# Lumber

Converts a DOM tree to an object

## Usage
```js
import Lumber from '/path/to/Lumber';

const parsed = Lumber.parse(`[HTML template]`);
```

## Issues
Yes. 

-  I might have missed some symbols in the text regular expression. Feel free to open a PR or file a bug.
-  Whitespaces between sibling/parent tags cause an infinite loop. Working on a fix.
