# xecjs-message
[![NPM Package](https://img.shields.io/npm/v/bitcoinjs-message.svg?style=flat-square)](https://www.npmjs.com/package/xecjs-message)
[![js-standard-style](https://cdn.rawgit.com/feross/standard/master/badge.svg)](https://github.com/feross/standard)

This is a fork of [bitcoinjs-message](https://github.com/bitcoinjs/bitcoinjs-message/). 

## Summary of changes from `bitcoinjs-message`

1. Segwit support removed from `verify`
2. `verify` accepts a valid XEC address

## Examples

``` javascript
import xecMessage from 'xecjs-message';

const verification =  xecMessage.verify(
                msg,
                xecAddress,
                signature,
            );

// returns true for valid signature, false for invalid
```


## LICENSE [MIT](LICENSE)
