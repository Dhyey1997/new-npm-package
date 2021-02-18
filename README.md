# new-npm-package
This package actually checks if the string is null, empty or undefined
## Usage
Install the package using npm:
npm install is-null-or-empty --save
Then, require the package and us it:
[Comment: The check if this usage is proper]
var isNullOrEmpty = require('is-null-or-empty');
console.log(isEmptyOrNull(""); // true
console.log(isNullOrEmpty("Hello World")) // false