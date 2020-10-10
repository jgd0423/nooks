# Usage

```js
import useBeforeLeave from "@nooks/use-before-leave";

const App = () => {
  const beforeLeave = () => {
    console.log("User is leaving...");
  };
  useBeforeLeave(beforeLeave);
  return (
    <div className="App">
      <h1>Hi</h1>
    </div>
  );
};
```
