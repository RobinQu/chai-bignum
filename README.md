# chai-bignum

chai assertions for bignum

Usage:

```
const chai = require('chai');
const bignum = require('bignum');
const expect = chai.expect;

chai.use(require('chai-bignum'));
expect('1234567').to.equal(bignum('1234567'));
```
