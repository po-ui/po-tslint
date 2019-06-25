# po-tslint

Package with lint rules used in the (PO) Portinari HTML Framework.

## INSTALL

```
npm i --save-dev @portinari/tslint
```


## USAGE

To apply lint rules used in PO projects you should, after installing the package, add the following lines of code in the `tslint.json` file, found at the root of your project.

```
"extends": [
  "@portinari/tslint"
]
```

Your file should look like this:

```
{
  "extends": [
    "@portinari/tslint"
  ],
  "rules": {
    // your personal rules.
  }
}
```

For more informations [Starting with po-tslint](https://po.portinari.com.br/guides/getting-started-po-tslint).