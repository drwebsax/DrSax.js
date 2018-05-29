# [DrSax.js](https://reactjs.org/) &middot; &middot; [![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/facebook/react/blob/master/LICENSE)

DrSax.js is a  audio library with JavaScript for Web Audio Works from Web Audio API.

* **Declarative:** React makes it painless to create interactive UIs. Design simple views for each state in your application, and React will efficiently update and render just the right components when your data changes. Declarative views make your code more predictable, simpler to understand, and easier to debug.


[Learn how to use DrSax.js in your own project](https://).

## Documentation

You can find the React documentation [on the website](https://reactjs.org/docs).  
It is divided into several sections:

* [Quick Start](https://reactjs.org/docs/hello-world.html)
* [Advanced Guides](https://reactjs.org/docs/jsx-in-depth.html)
* [API Reference](https://reactjs.org/docs/react-api.html)

## Examples

We have several examples [on the website](https://reactjs.org/). Here is the first one to get you started:

```jsx
class HelloMessage extends React.Component {
  render() {
    return <div>Hello {this.props.name}</div>;
  }
}

ReactDOM.render(
  <HelloMessage name="John" />,
  document.getElementById('container')
);
```

This example will render "Hello John" into a container on the page.

You'll notice that we used an HTML-like syntax; [we call it JSX](https://reactjs.org/docs/introducing-jsx.html). JSX is not required to use React, but it makes code more readable, and writing it feels like writing HTML. We recommend using [Babel](https://babeljs.io/) with a [React preset](https://babeljs.io/docs/plugins/preset-react/) to convert JSX into native JavaScript for browsers to digest.

## Installation

React is available as the `react` package on [npm](https://www.npmjs.com/). It is also available on a [CDN](https://reactjs.org/docs/cdn-links.html).

React is flexible and can be used in a variety of projects. You can create new apps with it, but you can also gradually introduce it into an existing codebase without doing a rewrite.

The recommended way to install React depends on your project. Here you can find short guides for the most common scenarios:

* [Trying Out React](https://reactjs.org/docs/try-react.html)
* [Creating a New Application](https://reactjs.org/docs/add-react-to-a-new-app.html)
* [Adding React to an Existing Application](https://reactjs.org/docs/add-react-to-an-existing-app.html)

## Contributing

The main purpose of this repository is to continue to evolve React core, making it faster and easier to use. Development of React happens in the open on GitHub, and we are grateful to the community for contributing bugfixes and improvements. Read below to learn how you can take part in improving React.

### [Code of Conduct](https://code.facebook.com/codeofconduct)

Facebook has adopted a Code of Conduct that we expect project participants to adhere to. Please read [the full text](https://code.facebook.com/codeofconduct) so that you can understand what actions will and will not be tolerated.

### [Contributing Guide](https://reactjs.org/contributing/how-to-contribute.html)

### License

React is [MIT licensed](./LICENSE).
