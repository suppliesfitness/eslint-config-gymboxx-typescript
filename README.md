### 1. Installing packages

```shell
npm install --save-dev \
  typescript@^4 \
  eslint@^7.32.0 \
  eslint-plugin-import@^2.22.1 \
  eslint-plugin-node@^11.1.0 \
  eslint-plugin-promise@^5.0.0 \
  @typescript-eslint/eslint-plugin@^4.0.1 \
  eslint-config-gymboxx-typescript@latest
``` 

### 2. Create Eslint configuration file

Create `.eslintrc.json` file at the top of the project directory like below.

```json
{
  "parserOptions": {
    "project": "./tsconfig.json"
  },
  "extends": "gymboxx-typescript",
  "rules": {
  }
}
```

## Reference
* https://github.com/standard/eslint-config-standard-with-typescript
* https://www.npmjs.com/package/eslint-config-airbnb-typescript
* https://www.npmjs.com/package/eslint-config-flitto-typescript
