![Alt text](./logo_light.svg) 
# blotjson

**Blot:**
> a procedure in which proteins or nucleic acids separated on a gel are transferred directly to an immobilizing medium for identification.


*blotjson* displays [JSON](https://www.json.org/json-en.html) in a browser directly from backend application code to make it easier to make sense of API responses, especially if they are not well documented.


## Basic Usage

### Node.js
**Installation**
```
npm i --save-dev blotjson
```
**Example**
```js
const blot = require('blotjson');

blot.visualise(JSON.stringify(
  ['foo', {'bar': ('baz', null, 1.0, 2)}]
));
```

See [redacted] for detailed documentation.


## Features
* JSON is pretty printed
* objects and arrays can be collapsed for simpler exploration 

## Why you might want to use *blotjson*
* An external application is not required. There is no need to copy/paste or export your data.
* An arbitrary number of JSON data can be visualised simply.


## Acknowledgements

The design of displaying the data is in part inspired by [Swagger](https://swagger.io) 
