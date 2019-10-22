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

---
### Notes
Red, Green, Refactor. 
Make sure you refactor your code after you pass your test.