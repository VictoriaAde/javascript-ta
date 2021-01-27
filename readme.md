# Javascript Track Assessment

## Instructions

This repo contains the accessment exercise for the Javascript Track
Please perform the following instructions.

* Fork this repository.
* Clone the repository to your local computer.
* Add your solution to the specificied position.
* Commit your solution.
* Push your update to your repository.
* Submit your repository URL on the provided google form.

## Example

```js
// src/index.js

// complete the function
function palindrom(str) {
  // code goes here

   // Lowercase the string and remove unwanted characters from it
  var re = /[^A-Za-z0-9]/g;
  var lowStr = str.toLowerCase().replace(re, '');

  // Use javascript built in functions
  var reverseStr = lowStr.split('').reverse().join(''); 

  //Check if reverseStr is equals to lowStr and returns a Boolean
  return reverseStr === lowStr;
}

function solution(arg) {
  return palindrom(arg);
}
```

## Running

``` shell
# run the solution
$: npm start <input>
```
## Testing
``` shell
$: npm test
```


## Need Help?
contact: ***
