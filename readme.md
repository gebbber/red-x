# Red X v1.0.0

Allows you to use a red X in the console!!

## With '`require`':
```javascript
const redX = require('../index.js');

console.log('Works from a CommonJs file', redX);
```

## With '`import`' from a Module:
```javascript
const redX = (await import('../index.js')).default;

console.log('Works from a module', redX);
```