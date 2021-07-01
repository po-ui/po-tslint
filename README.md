# po-tslint

:warning: __PO TSLint is deprecated.__

> Migramos para o @angular-eslint veja nossa [documentação de apoio](https://medium.com/totvsdevelopers/migrando-um-projeto-angular-com-tslint-para-o-eslint-d572e19786c1).

Package with lint rules used in the PO UI.

## Install

```
npm i --save-dev @po-ui/ng-tslint
```

## Usage

To apply lint rules used in PO projects you should, after installing the package, add the following lines of code in the `tslint.json` file, found at the root of your project.

```
"extends": [
  "@po-ui/ng-tslint"
]
```

Your file should look like this:

```
{
  "extends": [
    "@po-ui/ng-tslint"
  ],
  "rules": {
    // your personal rules.
  }
}
```

For more informations read [Starting with po-tslint](https://po-ui.io/guides/getting-started-po-tslint).
