# chrome-remote-interface-flowtype
provide a chrome-remote-interface library type at using flowtype

[![npm version](https://badge.fury.io/js/chrome-remote-interface-flowtype.svg)](https://badge.fury.io/js/chrome-remote-interface-flowtype)
[![CircleCI](https://circleci.com/gh/teitei-tk/chrome-remote-interface-flowtype/tree/master.svg?style=svg)](https://circleci.com/gh/teitei-tk/chrome-remote-interface-flowtype/tree/master)

## Dependencies
* flowtype 0.49.1 or latest

## Install
```bash
$ yarn add -D chrome-remote-interface-flowtype
```

or

```bash
$ npm install --save-dev chrome-remote-interface-flowtype
```

## Usage

```javascript
// @flow

import type {
  Debugger, DOM, Emulation,
  Input, Network, Page,
  Runtime, Security, Target
} from 'chrome-remote-interface-flowtype';
```

## Contributing
Bug reports and pull requests are welcome :) on GitHub at https://github.com/teitei-tk/chrome-remote-interface-flowtype

## LICENSE
* MIT License
