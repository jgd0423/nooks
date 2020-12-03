# Usage

```js
import useNotification from "@nooks/use-notification";

const App = () => {
  const triggerNotif = useNotification("I want to understand notification.", {
    body: "how does it works?"
  });
  return (
    <div className="App" style={{ height: "1000vh" }}>
      <button onClick={triggerNotif}>Hello</button>
    </div>
  );
};
```
