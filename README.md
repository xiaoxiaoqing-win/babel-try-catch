# babel-plugin-try-catch



## Example

**In**

```js
// input code
```

**Out**

```js
"use strict";

// output code
```

## Installation

```sh
$ npm install babel-plugin-try-catch
```

## Usage

### Via `.babelrc` (Recommended)

**.babelrc**

```json
{
  "plugins": ["try-catch"]
}
```

### Via CLI

```sh
$ babel --plugins try-catch script.js
```

### Via Node API

```javascript
require("babel-core").transform("code", {
  plugins: ["try-catch"]
});
```
