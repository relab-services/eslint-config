# @sergeyzwezdin/eslint-config

Shareable configuration for eslint (node)

## Usage

1. Install packages `eslint` and `@sergeyzwezdin/eslint-config`
```bash
npm install eslint --save-dev
npm install @sergeyzwezdin/eslint-config --save-dev
```
2. Update `package.json` 
```json
{
  "scripts": {
    "lint": "eslint . --ext ts,tsx"
  },
  "eslintConfig": {
    "extends": "@sergeyzwezdin/eslint-config"
  }
}
```

## License

Released under [MIT](/LICENSE) by [Sergey Zwezdin](https://github.com/sergeyzwezdin).
