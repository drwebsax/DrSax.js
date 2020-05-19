# [DrSax.js](https://drsax.github.io/DrSAX/lib.1.8.html) [![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://drsax.github.io/DrSAX/lib.1.8.html)

DrSax.js is a  audio library with JavaScript for Web Audio Works from Web Audio API.



## Examples

We have several examples [on the website](https://drsax.github.io/DrSAX/lib.1.8.html). Here is the first one to get you started:

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
You'll find mic demo application [mic and tunning](https://drsax.github.io/DrSAX/lib.1.8.html#micstart). 

## Download & Installation

It is also available on a [CDN](https://drwebsax.github.io/DrSax.js/js/drsax.1.9.1.21.js).

### License

DrSax.js is MIT licensed.
