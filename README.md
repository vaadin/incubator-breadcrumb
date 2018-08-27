[![Build Status](https://travis-ci.org/vaadin/incubator-breadcrumb.svg?branch=master)](https://travis-ci.org/vaadin/incubator-breadcrumb)
[![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/vaadin/web-components?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

# &lt;incubator-breadcrumb&gt;

[Live Demo ↗](https://incubator.app.fi/incubator-breadcrumb)

[&lt;incubator-breadcrumb&gt;](https://vaadin.com/components/incubator-breadcrumb) is a Web Component providing an easy way to display breadcrumb on web pages.

```html
  <incubator-breadcrumb>
    <incubator-breadcrumb-step separator=">" href="#">Home</incubator-breadcrumb-step>
    <incubator-breadcrumb-step separator=">" href="#">Directory</incubator-breadcrumb-step>
    <incubator-breadcrumb-step separator=">" href="#">Incubator Breadcrumb</incubator-breadcrumb-step>
  </incubator-breadcrumb>
```

[<img src="https://raw.githubusercontent.com/vaadin/incubator-breadcrumb/master/screenshot.png" width="200" alt="Screenshot of incubator-breadcrumb">](https://vaadin.com/components/incubator-breadcrumb)


## Installation

The Vaadin Incubator components are distributed as Bower packages.

### Polymer 2 and HTML Imports compatible version

Install `incubator-breadcrumb`:

```sh
bower i vaadin/incubator-breadcrumb --save
```

Once installed, import it in your application:

```html
<link rel="import" href="bower_components/incubator-breadcrumb/incubator-breadcrumb.html">
```

## Getting Started

Vaadin components use the Lumo theme by default.

## The file structure for Vaadin components

- `src/incubator-breadcrumb.html`

  Unstyled component.

- `theme/lumo/incubator-breadcrumb.html`

  Component with Lumo theme.

- `incubator-breadcrumb.html`

  Alias for theme/lumo/incubator-breadcrumb.html


## Running demos and tests in browser

1. Fork the `incubator-breadcrumb` repository and clone it locally.

1. Make sure you have [npm](https://www.npmjs.com/) installed.

1. When in the `incubator-breadcrumb` directory, run `npm install` and then `bower install` to install dependencies.

1. Run `polymer serve --open`, browser will automatically open the component API documentation.

1. You can also open demo or in-browser tests by adding **demo** or **test** to the URL, for example:

  - http://127.0.0.1:8080/components/incubator-breadcrumb/demo
  - http://127.0.0.1:8080/components/incubator-breadcrumb/test


## Running tests from the command line

1. When in the `incubator-breadcrumb` directory, run `polymer test`


## Following the coding style

We are using [ESLint](http://eslint.org/) for linting JavaScript code. You can check if your code is following our standards by running `gulp lint`, which will automatically lint all `.js` files as well as JavaScript snippets inside `.html` files.


## Contributing

  - Make sure your code is compliant with our code linters: `gulp lint`
  - Check that tests are passing: `polymer test`
  - [Submit a pull request](https://www.digitalocean.com/community/tutorials/how-to-create-a-pull-request-on-github) with detailed title and description
  - Wait for response from one of Vaadin components team members


## License

Commercial Vaadin Add-on License version 3 (CVALv3). For license terms, see LICENSE.

Vaadin collects development time usage statistics to improve this product. For details and to opt-out, see https://github.com/vaadin/vaadin-usage-statistics.
