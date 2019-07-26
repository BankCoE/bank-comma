# bank-comma

## Installation
This is `Node.js` module is convert to value with commas thousands. (e.g. 1000 -> 1,000)

Installation is done using the `npm install`

```npm
$ npm install bank-comma --save
```

---
## How to use

```javascript
const bankComma = require('bank-comma')

const number = bankComma(1000)
// log number is 1,000
```