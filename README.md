# Bad JSX in JS component

This is an example component to debug module loaders that don't support JSX in JS files.

## To use

```shell
yarn install bad-jsx-in-js-component
# OR npm install bad-jsx-in-js-component
```

```js
// App.jsx (or .tsx)
import JSXinJS from 'bad-jsx-in-js-component';

export default function App() {
  // Your component here
  return <JSXinJS />;
}
```
