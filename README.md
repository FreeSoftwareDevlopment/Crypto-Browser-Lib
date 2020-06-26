# Crypto-Browser-Lib

## Crypto:
Use Crypto:

it contain all functions from nodejs crypto lib but for browser!

### Example

This example generates the hmac from hello with the password world
Include File:
`<script src="https://cdn.jsdelivr.net/gh/FreeSoftwareDevlopment/Crypto-Browser-Lib@master/crypto.js"></script>`

Script:
```

<script>

const hmac = crypto.createHmac('sha256', 'world');

hmac.update('hello');

console.log(hmac.digest('hex'));

//  PRINTS:  7fd04df92f636fd450bc841c9418e5825c17f33ad9c87c518115a45971f7f77e

</script>

```

<pre>Example From https://nodejs.org/api/crypto.html#crypto_class_hmac</pre>
