 There is 2 ways of writing functions in React that I know of:

```js
function foo (some_text) {
    return (
        <div>{ some_text }</div>
    );
}
```

and

```js
const foo = (some_text) => <div>{ some_text }</div>;
```
