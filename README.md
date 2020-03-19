# po-tslint

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
