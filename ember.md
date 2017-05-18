# Ember

This document outlines the best practices for Ember-related projects.

- Use `eslint` instead of `jshint`.
- All actions should be placed on the view's `controllers`

#### Preferred `eslintrc.json`

```json
{
  "extends": "eslint:recommended",
  "env": {
    "node": true,
    "browser": true,
    "es6": true
  },
  "parserOptions": {
    "ecmaVersion": 2017,
    "sourceType": "module"
  },
  "rules": {
    "comma-dangle": ["error", "always-multiline"],
    "comma-spacing": ["error", { "before": false, "after": true }],
    "eol-last": ["error", "always"],
    "indent": ["error", 2],
    "no-multiple-empty-lines": ["error"],
    "no-trailing-spaces": ["error"],
    "no-var": "error",
    "prefer-const": 2,
    "quotes": ["error", "single"],
    "semi": ["error", "never"],
    "space-in-parens": ["error", "never"]
  }
}
```
