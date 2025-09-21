# DrSax.js[GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)

DrSax.js is a  audio library with JavaScript for Web Audio Works from Web Audio API.



## Examples

We have several examples. Here is the first one to get you started:

```jsx
var DSX = new DSX;
var gain = new DSX.Amp({gain: 0.5});
var saxInput = new DSX.Mic();
var tune = new DSX.Tunner("pitch","note");

saxInput.connect(gain);
tune.getAnalyser(saxInput);
gain.connect(DAC);                

```

## Download & Installation

It is also available on a [CDN](https://drsax.github.io/DrSAX/js/drsax.js).

### License

DrSax.js is MIT licensed.
