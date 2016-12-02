# Cipher - Your Source for Caesar Ciphers! #
Drupal - Module Development

## Features ##
The program will allow a user to input a shift value, shift direction and phrase and return a Caesar Cipher of the original phrase.

<img src="/sites/default/files/cipher.png" alt="screencap of my site">

## Technologies ##

Drupal, PHP, HTML, CSS and Bootstrap.

## Usage ##

To use the code, you can clone the repository at [https://github.com/jryanconklin/epicodus-drupal-cipher](https://github.com/jryanconklin/epicodus-drupal-cipher).

For best results, please:

- Clone the Repository
- Install the DB in MySQL
- Launch Project in MAMP

## Specifications ##

* It should present a custom form with 3 text inputs. We want you to use text inputs rather than radio buttons or menus so that you can practice validation.

* One input should be a shift value, one should be a direction, and the third should be the phrase to be encrypted.

* Then you should redirect to a second page to show the result - the encoded phrase. Here are a couple examples of input and output.

* The shift value is the number of places to shift each letter over.

* If the shift direction is "right" then you will add the shift value. For example: "a" with a shift value of 1 and a direction of right would become "b". A shift direction of "left" with a shift value of 1 would turn "b" into "a".

* If the shift amount takes you over the bounds of the alphabet then cycle back to the beginning. For example: a shift value of 3 with the direction of right would turn "z" into "c".

* Any spaces or punctuation in the input phrase should be ignored and reproduced in the final result without being shifted.

* Your final result should be in all lowercase.

### Additional Validation Rules ###

* The shift value must be a positive integer

* The shift direction must be either "left" or "right".

* The only special characters that should be allowed in your input phrase are spaces and punctuation.


## Author/s
J. Ryan Conklin

##License
This work can be used under the MIT License.
Copyright (c) 2016 J. Ryan Conklin
