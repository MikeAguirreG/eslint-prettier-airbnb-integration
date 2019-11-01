#Basic integration ESLINT, Prettier, Airbnb Style Guide with VS Code.

1. Install ESLint and Prettier VS Code extensions
2. npm init -y
3. npm i -D eslint prettier eslint-plugin-prettier eslint-config-prettier eslint-plugin-node eslint-config-node
4. npx install-peerdeps --dev eslint-config-airbnb
5. Create .prettierrc config file 6. node_modules/.bin/eslint --init, to create eslint config file
6. Basic setup .eslintrc.json

```javascript
{
    "extends": ["airbnb", "prettier", "plugin:node/recommended"],
    "plugins": ["prettier"],

    "rules": {
        "prettier/prettier": "warn",
        "no-unused-vars":"warn",
        "no-console":"off",
        "object-shorthand":"off"
    }
}
```
