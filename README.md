# Simple React Snippets

The essential collection of React Snippets and commands.

## Features

Only what you need and nothing more. **No Class Components. No PropTypes. No Redux. No React Native.**

Simply, simple React snippets.

These snippets were selected carefully from my own day-to-day React use. Not
everything in React is included here. This is a hand selected set of snippets
that work the way that you would expect, not just a copy of the documentation.

## Snippets

| Snippet | Renders                                       |
| ------- | --------------------------------------------- |
| `imr`   | Import React                                  |
| `ims`   | Import  useState                       |
| `imse`  | Import  useState useEffect             |
| `ffc`   | Function Component                            |
| `sfc`   | Stateless Function Component (Arrow function) |
| `uef`   | useEffect Hook                                |
| `ucb`   | useCallback Hook                              |
| `ssf`   | Functional setState                           |
| `usf`   | Declare a new state variable using State Hook |
| `cp`    | Context Provider                              |
| `cpf`   | Class Property Function                       |

## Full Expansions

### imr - Import React

```js
import  React from "react";
```

### ims - Import  useState

```js
import { useState } from "react";
```

### imse -  useState, useEffect

```js
import { useState, useEffect } from "react";
```

### ffc - Function Component

```js
function (|) {
    return ( | );
}

export default |;
```

### sfc - Stateless Function Component (Arrow function)

```js
const | = props => {
  return ( | );
};

export default |;
```

### uef - useEffect Hook

```js
useEffect(() => {
  |
}, []);
```

### ucb - useCallback Hook

```js
useCallback((val) => {
  |
}, []);
```

### ssf - Functional setState

```js
this.setState(prevState => {
  return { | : prevState.| }
});
```

### usf - Declare a new state variable using State Hook

```js
const [|, set|] = useState();
```

## Commands

### React: class to className

Changes all occurences of `class` in JSX to `className`. This transform is safe
to run multiple times on any document. No text needs to be selected as the
command is executed on the entire document.

![React: class to className](https://i.imgur.com/i1ZwvOu.gif)

## Thank You! ❤️

While I wrote the initial version of this extension, many people (too many to name) have helped make it what it is today. From providing TypeScript definitions to keeping up with changing API and best practices. If you are enjoying this extension, you have the great React community to thank.
