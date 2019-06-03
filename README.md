# Demonstration of [JSPrettier Issue](https://github.com/jonlabelle/SublimeJsPrettier/issues/181)

How to reproduce:

1. `yarn install`
2. Try to perform a format of `src/foo.js`, and see that the indentation does
   not change to 4 spaces. Ie. it does not respect `prettier.config.js`.
3. Run `yarn prettier "src/foo.js" --write` and see that the indentation _does_
   change to 4 spaces, as specified in `prettier.config.js`.
