# Usage

```js
import useBeforeLeave from "@nooks/use-before-leave";

const App = () => {
  const beforeLeave = () => {
    console.log("User is leaving...");
  };
  useBeforeLeave(beforeLeave);
  return <h1>Hello Nooks</h1>;
};
```
