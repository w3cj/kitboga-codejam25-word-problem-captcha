# Kitboga Code Jam - Word Problem Captcha

A word problem is presented to the user with lots of red herrings. The user must select the values from a drop down in a pre-determined calculation to solve the word problem and complete the captcha.

## How It Works

* A random word problem is chosen on load (8 problems available).
* Each value in the word problem is randomly generated.
* The answer calculation is presented to the user, but the user must select the value from a drop down for each variable.
* All problems are JSON files in [./captcha/problems/](./captcha/problems/) - the answers can be calculated using the answer JSON property in the JSON (nested arrays are calculated first).

## Configuration

Update the config values at the top of the script:

```js
/*
  Problems:
    1 - Bake Sale
    2 - Fundraiser
    3 - Steam Reservoir
    4 - Apple Orchard
    5 - Security Archive
    6 - Birthday Cake
    7 - Corn Cobs
    8 - Shopping
*/
const CONFIG = {
  SUBMIT_DELAY: 3000, // the time to wait before displaying the result
  AVAILABLE_PROBLEM_COUNT: 8, // the number problem json files available
  PROBLEM_ID: 0, // sets a static problem id to load, 0 = random
};
```

Try it out here: [https://w3cj.github.io/kitboga-codejam25-word-problem-captcha/](https://w3cj.github.io/kitboga-codejam25-word-problem-captcha/)