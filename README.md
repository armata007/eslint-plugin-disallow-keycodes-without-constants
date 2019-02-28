# eslint-plugin-disallow-keycodes-without-constants

Disallow keycodes without constants

## Installation

You'll first need to install [ESLint](http://eslint.org):

```
$ npm i eslint --save-dev
```

Next, install `eslint-plugin-disallow-keycodes-without-constants`:

```
$ npm install eslint-plugin-disallow-keycodes-without-constants --save-dev
```

**Note:** If you installed ESLint globally (using the `-g` flag) then you must also install `eslint-plugin-disallow-keycodes-without-constants` globally.

## Usage

Add `disallow-keycodes-without-constants` to the plugins section of your `.eslintrc` configuration file. You can omit the `eslint-plugin-` prefix:

```json
{
    "plugins": [
        "disallow-keycodes-without-constants"
    ]
}
```


Then configure the rules you want to use under the rules section.

```json
{
    "rules": {
        "disallow-keycodes-without-constants/rule-name": 2
    }
}
```

## Supported Rules

* Fill in provided rules here





