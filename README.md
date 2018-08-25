# eslint-plugin-prop-types-csharp

Proxy for `@creuna/prop-types-csharp/eslint-plugin`

Source:

```js
module.exports = require("@creuna/prop-types-csharp/eslint-plugin");
```

This package simply imports and exports `@creuna/prop-types-csharp/eslint-plugin` at whichever version you are using.

Documentation for this plugin can be found [here](https://github.com/Creuna-Oslo/prop-types-csharp#eslint).

## Why?

Because in `eslint` the only way to load a plugin is to create an npm package with a name starting with `eslint-plugin-`. In `@creuna/prop-types-csharp`, everything is tightly coupled and it makes more sense to have the actual code of the eslint plugin live there.
