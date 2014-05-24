customevent-polyfill
====================

A ployfill for CustomEvent

This is basically an extended version of the [polyfill provided by MDN](https://developer.mozilla.org/en-US/docs/Web/API/CustomEvent).

## Why another CustomEvent polyfill?

Unfortunately, the MDN polyfill does not cover Browsers < IE 9, including Android Stock Browser on Gingerbread. As I needed support for these browsers and could not find a polyfill that fits this need, I created my own.

## Usage
Download this repo and include customevent-polyfill.min.js in your project. You can install customevent-polyfill via bower as well.

    bower install customevent-polyfill