# react-router-defer

[![GitHub stars](https://img.shields.io/github/stars/codejamninja/react-router-defer.svg?style=social&label=Stars)](https://github.com/codejamninja/react-router-defer)

> Adds deferred asynchronous rendering to react router

Please ★ this repo if you found it useful ★ ★ ★


## Features

* Adds asynchronous `componentDefer` method prop to `Route` component
* Adds asynchronous `renderDefer` method prop to `Route` component
* Adds asynchronous deferred hook to `history.push`


## Installation

```sh
npm install --save react-router-defer
```


## Dependencies

* [NodeJS](https://nodejs.org)


## Usage

```js
import React, { Component } from 'react';
import { Switch, Route } from 'react-router-defer';

export default class Routes extends Component {
  render() {
    return (
      <Switch>
        <Route exact path="/" componentDefer={() => import('./Home')} />
        <Route componentDefer={() => import('./NotFound')} />
      </Switch>
    );
  }
}
```

[Contribute](https://github.com/codejamninja/react-router-defer/blob/master/CONTRIBUTING.md) usage docs


## Support

Submit an [issue](https://github.com/codejamninja/react-router-defer/issues/new)


## Screenshots

[Contribute](https://github.com/codejamninja/react-router-defer/blob/master/CONTRIBUTING.md) a screenshot


## Contributing

Review the [guidelines for contributing](https://github.com/codejamninja/react-router-defer/blob/master/CONTRIBUTING.md)


## License

[MIT License](https://github.com/codejamninja/react-router-defer/blob/master/LICENSE)

[Jam Risser](https://codejam.ninja) © 2018


## Changelog

Review the [changelog](https://github.com/codejamninja/react-router-defer/blob/master/CHANGELOG.md)


## Credits

* [Jam Risser](https://codejam.ninja) - Author


## Support on Liberapay

A ridiculous amount of coffee ☕ ☕ ☕ was consumed in the process of building this project.

[Add some fuel](https://liberapay.com/codejamninja/donate) if you'd like to keep me going!

[![Liberapay receiving](https://img.shields.io/liberapay/receives/codejamninja.svg?style=flat-square)](https://liberapay.com/codejamninja/donate)
[![Liberapay patrons](https://img.shields.io/liberapay/patrons/codejamninja.svg?style=flat-square)](https://liberapay.com/codejamninja/donate)
