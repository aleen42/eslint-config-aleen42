<h2 align="center"> Personal ESLint config files </h2>

[![eslint](https://aleen42.github.io/badges/src/eslint.svg)](http://eslint.org/docs/rules/) [![npm](https://img.shields.io/npm/v/eslint-config-aleen42.svg)](https://npmjs.org/package/eslint-config-aleen42)

### Usage

To use this config, add this to your `package.json`

```json
{
  "devDependencies"  : {
    "eslint"                 : "4.16.0",
    "eslint-config-aleen42" : "1.0.0"
  }
}
```

or install manually

```bash
npm install --save-dev eslint eslint-config-aleen42
```


Then, add this to your `.eslintrc.yaml` file: 

- Using standard rules

    ```yaml
    extends: aleen42
    ```

- Applying compliant rules (old IE compatible)

    ```yaml
    extends: aleen42/config/compliant.yaml
    ```


### Learn more

For the full listing of rules that eslint supports, and more, visit 
For more information the full listing of rules, editor plugins, FAQs, and more, visit the
[ESLint official site](http://eslint.org/docs/rules/).

### :fuelpump: How to contribute

Have an idea? Found a bug? See [how to contribute](https://aleen42.gitbooks.io/personalwiki/content/contribution.html).

### :scroll: License

[MIT](https://aleen42.gitbooks.io/personalwiki/content/MIT.html) © aleen42
