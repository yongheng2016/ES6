# ES6特性
## Array
### `reduce`(减少、累加)
```js
function sum(arr) {
    return arr.reduce((sum,val,index,arr) => sum+val)
}
```
