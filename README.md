# ESLinter support for any javascript ES5, ES2015, ES.next and React projects

[![npm version](https://badge.fury.io/js/eslint-modules-standard-deviation.svg)](https://badge.fury.io/js/eslint-modules-standard-deviation)

> Add linter settings easily to any javascript `ES5`, `ES2015`, `ES.next` or `React` project using shared eslint config, [eslint-config-standard-deviation](https://github.com/bySabi/eslint-config-standard-deviation), and [ESLint](http://eslint.org/)

## Installation

### npm

```bash
npm install eslint eslint-modules-standard-deviation --save-dev
```

## Usage
Add `extends` to project `.eslintrc`
```json
{
  "extends": ["standard-deviation"]
}
```

### [optional] enable/disable [eslint rules](http://eslint.org/docs/rules/)
```json
{
  "extends": ["standard-deviation"],
  "rules": {
    "space-before-function-paren": ["2", "always"]
  }
}

Add scripts to `package.json`
```json
"scripts": {
  "lint": "eslint . --ext .js,.jsx",
  "testonly": "echo \"Error: no test specified\" && exit 1",
  "test": "npm run lint && npm run testonly"
}
```

## Projects using `eslint-modules-standard-deviation`
* [react-scrollchor](https://github.com/bySabi/react-scrollchor)
* [react-scrollaware](https://github.com/bySabi/react-scrollaware)

## Contributing

* Documentation improvement
* Feel free to send any PR

## License

[ISC][isc-license]

[isc-license]:./LICENSE
