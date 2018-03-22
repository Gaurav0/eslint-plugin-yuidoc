# eslint-plugin-yuidoc

ESLint rules for YUIDoc

### WIP

## Installation

You'll first need to install [ESLint](http://eslint.org):

```
$ npm i eslint --save-dev
```

Next, install `eslint-plugin-yuidoc`:

```
$ npm install eslint-plugin-yuidoc --save-dev
```

**Note:** If you installed ESLint globally (using the `-g` flag) then you must also install `eslint-plugin-yuidoc` globally.

## Usage

Add `yuidoc` to the plugins section of your `.eslintrc` configuration file. You can omit the `eslint-plugin-` prefix:

```json
{
    "plugins": [
        "yuidoc"
    ]
}
```


Then configure the rules you want to use under the rules section.

```json
{
    "rules": {
        "yuidoc/rule-name": 2
    }
}
```

## Supported Rules

* Fill in provided rules here
