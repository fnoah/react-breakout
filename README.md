<h2 align="center">
  React Breakout
</h2>

<p align="center">
  Lightweight hook for responsive breakpoints in your React components
</p>

<p align="center">
  <a href="https://www.npmjs.com/package/react-breakout"><img src="https://img.shields.io/npm/v/react-breakout.svg?style=flat-square"></a>
  <a href="https://github.com/fnoah/react-breakout/blob/master/LICENSE"><img src="https://img.shields.io/npm/l/react-breakout.svg?style=flat-square"></a>
</p>

---

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
