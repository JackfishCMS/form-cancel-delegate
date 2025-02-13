# @jackfish/form-cancel-delegate

Show a confirmation dialog if model changes will be lost when navigating from a form

## WARNING

From 3.0.0 your project will require at least `schemata@6` and support for a pug@3 runtime.

## Installation

    npm install --save @jackfish/form-cancel-delegate

## Usage

On a Backbone view that has an `initialModel` property:

```js
var formCancelDelegate = require('@jackfish/form-cancel-delegate')(logger)
formCancelDelegate.call(view) // Needs to be executed in the context of the view
```

## Example:

![Example](https://i.cloudup.com/Q6FUnStL9S-2000x2000.png)

## Credits

Built by developers at [Clock](http://clock.co.uk).

## Licence

Licensed under the [New BSD License](http://opensource.org/licenses/bsd-license.php)
