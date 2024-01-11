# @sergeyzwezdin/eslint-config-node

Shareable configuration for eslint (node)

## Usage

1. Install packages `eslint` and `@sergeyzwezdin/eslint-config-node`
```bash
npm install eslint --save-dev
npm install @sergeyzwezdin/eslint-config-node --save-dev
```
2. Add `.eslintrc.json`
```json
{
  "extends": "@sergeyzwezdin/eslint-config-node"
}
```

3. Update `scripts` section of `package.json` 
```json
{
  "scripts": {
    "lint": "eslint"
  }
}
```

## License

Released under [MIT](/LICENSE) by [Sergey Zwezdin](https://github.com/sergeyzwezdin).
