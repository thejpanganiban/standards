# React

This document outlines the best practices for React-related projects.

#### Preferred `eslintrc.json`

```json
{
  "parser": "babel-eslint",
  "extends": ["react-app", "eslint:recommended", "plugin:react/recommended"],
  "rules": {
    "array-bracket-spacing": "error",
    "block-spacing": "error",
    "comma-dangle": ["error", "always-multiline"],
    "comma-spacing": "error",
    "eol-last": "error",
    "indent": ["error", 2],
    "jsx-quotes": ["error", "prefer-single"],
    "keyword-spacing": "error",
    "no-multi-spaces": "error",
    "no-multiple-empty-lines": "error",
    "no-trailing-spaces": "error",
    "no-unneeded-ternary": ["error", { "defaultAssignment": false }],
    "no-var": "error",
    "object-curly-spacing": ["error", "always"],
    "prefer-const": "error",
    "quotes": ["error", "single"],
    "react/jsx-closing-bracket-location": "error",
    "react/jsx-curly-spacing": "error",
    "react/jsx-equals-spacing": "error",
    "react/jsx-indent": ["error", 2],
    "react/jsx-no-bind": "error",
    "react/jsx-pascal-case": "error",
    "react/jsx-wrap-multilines": "error",
    "react/sort-prop-types": "error",
    "semi": ["error", "never"],
    "space-before-blocks": "error",
    "space-before-function-paren": ["error", "never"],
    "space-in-parens": ["error", "never"]
  }
}
```

