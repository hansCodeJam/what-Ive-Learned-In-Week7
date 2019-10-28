### What I've Learned in Week 8

### For loops

Loops can execute a block of code a number of times.

Example

```javascript
function doubleAll(arr) {
  let newArray = [];

  for(let i = 0; i < arr.length; i++){
    newArray.push(arr[i] * 2)
  }
  return newArray;
}

double([3,2,13,])
//[6, 4, 26]
```

Slice Methods

The slice() method returns the selected elements in an array, as a new array object.

Example 

```javascript
let fruits = ["Banana", "Orange", "Lemon", "Apple", "Mango"];
let citrus = fruits.slice(1, 3);

console.log(citrus);
//Orange, Lemon
```

Bug fixing

Exercise: https://github.com/ci-wdi-900/cripples-bastards-and-broken-things
