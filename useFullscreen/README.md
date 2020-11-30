# Usage

```js
import useFullscreen from "@nooks/use-fullscreen";

const App = () => {
  const onFullS = (isFull) => {
    console.log(isFull ? "We are full" : "We are small");
  };

  const { element, triggerFull, exitFull } = useFullscreen(onFullS);
  return (
    <div className="App" style={{ height: "1000vh" }}>
      <div ref={element}>
        <img
          src="https://66.media.tumblr.com/513f7df7d9a1539c4c6d02c308f63ef9/tumblr_inline_pnkpbfV46O1qfex1b_540.jpg"
          alt="drake's"
        />
        <button onClick={exitFull}>Exit FullScreen</button>
      </div>
      <button onClick={triggerFull}>Make FullScreen</button>
    </div>
  );
};
```
