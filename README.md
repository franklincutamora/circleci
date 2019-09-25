# Must Have Config
==============================

.eslintrc.js
    module.exports = {
        "env": {
            "browser": true,
            "es6": true
        },
        "extends": "eslint:recommended",
        "globals": {
            "Atomics": "readonly",
            "SharedArrayBuffer": "readonly"
        },
        "parserOptions": {
            "ecmaVersion": 2018,
            "sourceType": "module"
        },
        "rules": {
        }
    };

==============================

.stylelintrc
    {
        "rules": {
            "at-rule-no-unknown": true,
            "block-no-empty": true,
            "comment-no-empty": true,
            "declaration-block-no-duplicate-properties": true,
            "declaration-block-no-redundant-longhand-properties": true,
            "declaration-block-no-shorthand-property-overrides": true,
            "max-empty-lines": 1,
            "no-descending-specificity": true,
            "no-duplicate-selectors": true,
            "no-empty-source": true,
            "no-extra-semicolons": true,
            "property-no-unknown": true,
            "unit-no-unknown": true,
        }
    }

==============================
.gitattributes
.gitignore
.htaccess