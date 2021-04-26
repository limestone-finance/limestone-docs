---
description: Simple example of limestone-api usage
---

# Usage

```javascript
// Using Node.js `require()`
const limestone = require('limestone-api');

// Using ES6 imports
import limestone from 'limestone-api';
```

Then you can fetch the prices with just a single line of code

```javascript
const price = await limestone.getPrice("AR");

console.log(price.value); // latest price value for AR token (in USD)
console.log(price.timestamp); // the exact timestamp of the price
```

