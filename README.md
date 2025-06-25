# Kitboga Code Jam - Word Problem Captcha

A word problem is presented to the user with lots of red herrings. The user must select the values from a drop down in a pre-determined calculation to solve the word problem and complete the captcha.

## How It Works

* Each value in the word problem is randomly generated on load.
* The answer calculation is presented to the user, but the user must select the value from a drop down for each variable.
* All problems are JSON files in [./captcha/problems/](./captcha/problems/) - the answers can be calculated using the answer JSON property in the JSON (nested arrays are calculated first).