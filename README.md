# litecollective
A lightweight package that provides exact the same postinstall action as the original opencollective package but with a much smaller footprint (200KB vs 24MB). 

## Install
```
$ npm install --save litecollective
```

## Config
Add the following to your `package.json`: 

```json
{
  "scripts": {
    "postinstall": "litecollective"
  },
  "collective": {
    "logo": "https://opencollective.com/webpack/logo.txt",
    "url": "https://opencollective.com/webpack"
  }
}
```