# What-I-Learned-In-Week-7
### Mapping
Changing all the items on an array.

---
### For Loops
A different way to loop in JS.
```
for (let i = 0; i < arr.length; i++) {
    console.log(arr[i] * 2);
}
```

---
### Methods
`str.slice(start, end)` - The end does not include that number. Slice **does not** mutate the underlying value.
* `str.slice(-4)` will take the last four strings.

`splice(start, how many to delete)` - Splice **does** mutates the underlying value.

**Optional parameters** will make your code shorter but be careful with parameters that are `undefined`.

Breakdown the method and write down what it does specifically. I've been struggling with finding the solution for what works under the hood. Concepts like, if two values do not equal each other loop and return false. Return the true value outside of the for loop.

---
### Notes
* Red, Green, Refactor. 
    * Make sure you refactor your code after you pass your test.
* `arr[i][0]` - double index will give you the array's index and 0 position of the item.
* Get into the habit of using Ternary Operator for best use cases.