Create an array called cheer and give it the values `[1, 2, 3, 4]`.

Write a loop that iterates over the array, doubles each element, and stores it in the same index it got it from. It should look like: `[2, 4, 6, 8]`

```javascript
// Create a variable to store our arry
const cheer = [1, 2, 3, 4];

// Loop through the array and add the index to itself
for (let i = 0; i < cheer.length; i++) {
    cheer[i] = cheer[i] + cheer[i];
}

// Log out Cheer
console.log(cheer);  // --> [2, 4, 6, 8]
```