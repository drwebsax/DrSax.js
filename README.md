# [DrSax.js](https://reactjs.org/)  &middot; [![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/facebook/react/blob/master/LICENSE)

DrSax.js is a  audio library with JavaScript for Web Audio Works from Web Audio API.

* **Declarative:** React makes it painless to create interactive UIs. Design simple views for each state in your application, and React will efficiently update and render just the right components when your data changes. Declarative views make your code more predictable, simpler to understand, and easier to debug.


[Learn how to use DrSax.js in your own project](https://drwebsax.github.io/DrSax.js/index.html).

## Tutorial site

You can find the DrSax.js documentation [on the website](https://drwebsax.github.io/DrSax.js/index.html).  
It is divided into several sections:

* Download
* Demo Appllication
* code

## Examples

We have several examples [on the website](https://reactjs.org/). Here is the first one to get you started:

```jsx
var DSX = new DSX;
var gain = new DSX.Amp({gain: 0.5});
var saxInput = new DSX.Mic();
var tune = new DSX.Tunner("pitch","note");

saxInput.connect(gain);
tune.getAnalyser(saxInput);
gain.connect(DAC);                
      
```

This example will work mic input and tunning.
You'll find mic demo application [mic and tunning](https://reactjs.org/docs/introducing-jsx.html). 

## Download & Installation

DrSax is available as the `react` package on [npm](https://www.npmjs.com/).
It is also available on a [CDN](https://).

### License

React is MIT licensed.
