# @sergeyzwezdin/eslint-config-node

Shareable configuration for eslint (node)

## Usage

1. Install packages `eslint` and `@sergeyzwezdin/eslint-config-node`
```bash
npm install eslint --save-dev
npm install @sergeyzwezdin/eslint-config-node --save-dev
```
2. Update `package.json` 
```json
{
  "scripts": {
    "lint": "eslint . --ext ts,tsx"
  },
  "eslintConfig": {
    "extends": "@sergeyzwezdin/eslint-config-node"
  }
}
```

## License

Released under [MIT](/LICENSE) by [Sergey Zwezdin](https://github.com/sergeyzwezdin).
