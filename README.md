# JavaScript-waitForElement
Async Wait For Element Function - JavaScript

## USE

Parameters:
1. `Selector`
2. `Timeout`
3. `Interval`

```js
waitForElement('.test', 5000, 100).then((el) => {
	console.log(el);
});
```
or 
```js
let element = await waitForElement('.test', 5000, 100);
console.log(el);
```
