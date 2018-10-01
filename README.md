# honestica-tslint
This repo holds honestica's common tslint rules. To use them, just npm install it:

`npm install --save-dev honestica-tslint`

Then, in your tslint.json file for your project, you can reference the package of rules with extends, and override some if necessary.

```javascript
{
    "extends": "honestica-tslint/tslint-config",
    "rules": {
        "no-addition": true
    }
}
```
