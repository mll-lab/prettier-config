# prettier-config

The shareable prettier configuration of MLL

## Installation

```shell
yarn add --dev @mll-lab/prettier-config
```

## Usage

```js
// .prettierrc.js
module.exports = require('@mll-lab/prettier-config');

// For customization
module.exports = {
    ...require('@mll-lab/prettier-config'),
    ...
};
```
