# ES6特性
## Array
### `reduce`(减少、累加)
```js
function sum(arr) {
    return arr.reduce( (sum,val,index,arr) => sum+val )
}
sum([1,2,3,4,5])  //15
```
