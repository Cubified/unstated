## Unstated

A simple stateless password manager, inspired by [LessPass](https://lesspass.com).

[Try it here](https://cubified.github.io/unstated)

### Screenshot

![screenshot](https://github.com/Cubified/unstated/blob/master/screenshot.png)


### Technical Explanation

Password generation is a two-step process:
1. A combination of the site name, username, and master password is SHA512/224 hashed.
2. The output hash is encoded using a modified form of the Base64 encoding algorithm, mapping 3 character input segments to 4 characters of output.

### To-Do

- Write Chrome extension to automate password generation
