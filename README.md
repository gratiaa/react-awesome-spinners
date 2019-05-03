# react-awesome-spinners

[![NPM version](https://img.shields.io/npm/v/react-awesome-spinners.svg)](https://www.npmjs.com/package/react-awesome-spinners)
[![Build Status](https://travis-ci.org/tienpham94/react-awesome-spinners.svg?branch=master)](https://travis-ci.org/tienpham94/react-awesome-spinners)
[![Coverage Status](https://coveralls.io/repos/github/tienpham94/react-awesome-spinners/badge.svg?branch=master)](https://coveralls.io/github/tienpham94/react-awesome-spinners?branch=master)
[![minified-size](https://img.shields.io/bundlephobia/min/react-awesome-spinners.svg)](https://bundlephobia.com/result?p=react-awesome-spinners@1.1.0)
[![js-standard-style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg)](http://standardjs.com/)
[![MIT License](https://img.shields.io/npm/l/react-css-spinners.svg)](https://github.com/alex996/react-css-spinners/blob/master/LICENSE)

Loading spinners for React, built with styled-components.

## Installation

### npm

```sh
npm i react-awesome-spinners
```

### yarn

```sh
yarn add react-awesome-spinners
```

## Usage

1. Import any spinner

```js
import { Ring } from 'react-awesome-spinners'
```

2. Use it as usual

```js
import React, { useState } from "react";
import ReactDOM from "react-dom";
import { Ring } from "react-awesome-spinners";

const App = () => {
  const [loading, setLoading] = useState(true)
    
  return (
      loading && <Ring />
  );
}

ReactDOM.render(<App />, document.getElementById("root"));
```

## Default Props

Common default props for all loaders:

```js
size: 64,
color: '#00bfff',
sizeUnit: 'px'
```

## Examples

- [Create-React-App](./exampes/cra)
- [Server-Side Rendering](./exampes/ssr)