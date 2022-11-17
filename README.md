# _⚠️ MOVED TO [OpenFn/adaptors](https://github.com/OpenFn/adaptors)! ⚠️_

**N.B.: New versions are available at:
https://github.com/OpenFn/adaptors/tree/main/packages/facebook**

# Language Facebook (Archived)
=================

Language Pack for building expressions and operations to interact with the Facebook Messenger API.

Documentation
-------------

## sample configuration

```json
{
  "accessToken": "yOuR-aCcEsS-tOkEn",
}
```

## postMessage
#### sample expression using operation
```js
postMessage({
  "recipient": {
    "id": "<PSID>"
  },
  "message": {
    "text": "<YOUR MESSAGE GOES HERE>"
  }
})
```

Development
-----------

Clone the repo, run `npm install`.

Run tests using `npm run test` or `npm run test:watch`

Build the project using `make`.
