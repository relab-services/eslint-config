# @sergeyzwezdin/eslint-config

Shareable configuration for eslint

## Usage

1. Install packages `eslint` and `@sergeyzwezdin/eslint-config`
```bash
npm install eslint --save-dev
npm install @sergeyzwezdin/eslint-config --save-dev
```
2. Update `package.json` 

**Node project:**
```json
{
  "scripts": {
    "lint": "eslint . --ext ts,tsx"
  },
  "eslintConfig": {
    "extends": "@sergeyzwezdin/eslint-config/node"
  }
}
```

**Next project:**
```json
{
  "scripts": {
    "lint": "eslint . --ext ts,tsx"
  },
  "eslintConfig": {
    "extends": "@sergeyzwezdin/eslint-config/next"
  }
}
```

## Available configurations

- Node: `@sergeyzwezdin/eslint-config/node`
- Next: `@sergeyzwezdin/eslint-config/next`

## License

Released under [MIT](/LICENSE) by [Sergey Zwezdin](https://github.com/sergeyzwezdin).
