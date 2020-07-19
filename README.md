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

How to use

```jsx
import React, { useState } from "react";
import { useDebounce } from "react-relaxed";

const App = () => {
  const [value, setValue] = useState("initial value");
  const [debouncedValue] = useDebounce(value, 500);

  return (
    <div>
      <input value={value} onChange={(event) => setValue(event.target.value)} />
      <p>{value}</p>
      <p>{debouncedValue}</p>
    </div>
  );
};
```
