# Stylelint Rules

## Description

This package contains a standard set of stylelint rules to be used across Strut Software Solutions projects and Rithm Software projects. This is to ensure each project has the same set of rules to keep projects consistent.

Lint rules exist for the following uses:

* SCSS

## Installation

From the root folder of your project, install the package with the following command:

```javascript
npm i @strut-software/stylelint-config --save-dev
```

## Usage

Once the package is installed, add the desired rulesets to the `"extends"` section of the `.stylelintrc.json` in the root of your project:

```javascript
{
    ...
            "extends": [
                "@strut-software/stylelint-config/scss"
            ],
            ...
        }
        ...
    ]
}
```

Afterwards, you will be able to run your desired lint command to use the newly-imported lint rules.

> **NOTE: Keeping this package up to date is highly recommended. Be sure that the version number in your `package.json` contains a `^` before the version number to update to the newest minor version when using `npm update`.**

**Example:**

```javascript
"devDependencies": {
    ...
    "@strut-software/stylelint-config": "^1.0.7",
    ...
}
```
