<div align="center">
<h1>React Breakout</h1>

<p>Lightweight hook for responsive breakpoints in your React components</p>
</div>

---

[![npm](https://img.shields.io/npm/v/react-breakout.svg?style=flat-square)](https://www.npmjs.com/package/react-breakout)
[![MIT License](https://img.shields.io/npm/l/react-breakout.svg?style=flat-square)](https://github.com/fnoah/react-breakout/blob/master/LICENSE)

## Installation

### NPM

```
npm install --save react-breakout
```

### Yarn

```
yarn add react-breakout
```

## Usage

```jsx
import React from "react";
import { useBreakpoint } from "react-breakout";

const App = () => {
  const isDesktop = useBreakpoint("md");

  return (
    <div>
      <p>{isDesktop ? "YES" : "NO"}</p>
    </div>
  );
};
```
