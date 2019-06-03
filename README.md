# Demonstration of [JSPrettier Issue](https://github.com/jonlabelle/SublimeJsPrettier/issues/181)

How to reproduce:

1. `yarn install`
2. Try to perform a format of `src/foo.js`, and see that the indentation does
   not change to 4 spaces. Ie. it does not respect `prettier.config.js`.
