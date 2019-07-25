### stealth
---
https://github.com/cryptocoinjs/stealth

```js
var Stealth = require('stealth')

var addr = 'xxx'
var stealth = Stealth.fromString(addr)

var keypair = require('coinkey').createRandom()

var payToAddress = stealth.genPaymentAddress(key.privateKey)

var Stealth = require('stealth')
var payloadKeyPair = require('coinkey').createRandom()
var scanKeyPair = require('coinkey').createRandom()

var stealth = new Stealth({
  payloadPrivKey: payloadKeyPair.privateKey,
  payloadPubKey: payloadKeyPair.publicKey,
  scanPrivKey: scanKeyPair.privateKey,
  scanPubKey: scanKeyPair.publicKey
})

var addr = stealth.toString()

var opReturnPubKey = /* */
var pubKeyHashWithPayment = /* */

var keypair = stealth.checkPaymentPubKeyHash(opReturnPubKey, pubKeyHashWithPayment)

if (keypair == null) {
  console.log('payment is not mine')
} else {
  console.log('payment is mine')
  
  console.log(keypair.privKey)
}

```

```
```

```
```


