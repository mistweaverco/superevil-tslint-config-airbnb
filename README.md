# Super Evil TSLint Config Airbnb

A super evil [TSLint config][tslint-website]
for the [Airbnb JavaScript Style Guide][airbnb-js-website]

This project started as a hard-fork of the *tslint-config-airbnb* nodejs
package, because it lacked some rules and wasn't as strict as
[Ströer Digital Publishing GmbH][sdp-github] wanted it to be.

# Rules

For a complete overview of all rules that are applied/enforced by this package,
see [Rules.md][rules-doc].

# Prerequisites

* [yarn][yarn-install] or [npm][npm-install]
* [typescript][typescript-npm]

# Common pitfalls

## Using a different `tslint.json` configuration file

Make sure that you're using the exact
[same TSLint configuration file](#tslint-configuration) as described.

## Using an `.editorconfig` file

If you're using an `.editorconfig` file, make sure it applies the same rules
that are part of this package.

## Using webpack

If you're using an `webpack`, make sure that the configuration file(s) for
webpack don't interfere with the rules that are applied/enforced by this
package.

Check the `tslint-loader` section of your webpack config, if you happen to use
linters with webpack.

## Installation

You can either install it via [yarn][yarn] (the preferred way),
or with [npm][npm-install].

### With yarn

```bash
yarn add @superevilmegaco/superevil-tslint-config-airbnb
```

### With npm

```bash
npm install --save @superevilmegaco/superevil-tslint-config-airbnb
```

### TSLint configuration

Simply put this into your `tslint.json` configuration file:

```json
{
  "defaultSeverity": "error",
  "extends": "@superevilmegaco/superevil-tslint-config-airbnb",
  "jsRules": {},
  "rules": {}
}
```

### Visual Studio Code

In Visual Studio Code, press
<kbd>CTRL</kbd> + <kbd>SHIFT</kbd> + <kbd>P</kbd>,
then enter `Extensions: Install Extensions` and search for `TSLint`.

Select the [TSLint Plugin][vscode-tslint-plugin] and install it.

After the installation completes, reload the IDE.

## Rules

* [tslint][tslint]
* [tslint-consistent-codestyle][tslint-consistent-codestyle]
* [tslint-eslint-rules][tslint-eslint-rules]
* [tslint-microsoft-contrib][tslint-microsoft-contrib]



[tslint-website]: https://palantir.github.io/tslint/usage/tslint-json/
[airbnb-js-website]: https://github.com/airbnb/javascript
[tslint]: https://www.npmjs.com/package/tslint
[tslint-consistent-codestyle]: https://www.npmjs.com/package/tslint-consistent-codestyle
[tslint-eslint-rules]: https://www.npmjs.com/package/tslint-eslint-rules
[tslint-microsoft-contrib]: https://www.npmjs.com/package/tslint-microsoft-contrib
[yarn-install]: https://yarnpkg.com/en/docs/install
[yarn]: https://yarnpkg.com/
[npm-install]: https://www.npmjs.com/get-npm
[vscode-tslint-plugin]: https://marketplace.visualstudio.com/items?itemName=eg2.tslint
[typescript-npm]: https://www.npmjs.com/package/typescript
[sdp-github]: https://github.com/stroeerdigitalpublishing
[rules-doc]: Rules.md

