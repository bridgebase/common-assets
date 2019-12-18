# Bridgebase Common Assets

This repo aims at centralizing assets for the different BBO applications (Homepage, landings, webutils, v3, ...)

## Installation

Yarn style:

```bash
yarn add ssh://git@github.com:bridgebase/common-assets.git#0.1.*
```

NPM flavor:

```bash
npm i --save ssh://git@github.com:bridgebase/common-assets.git#0.1.0
``` 

_NPM doesn't seem to support wildcard versions along with a custom git repository_

## SCSS Usage

Import variables & icons:
```scss
@import '~@bridgebase/common-assets/src/scss/variables';
@import '~@bridgebase/common-assets/src/scss/icons';
```
