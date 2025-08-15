# Writing a For Loop in JavaScript
![header image](https://articles.geekster.in/wp-content/uploads/2024/04/7-3.png)

In JavaScript, **loops** allow you to repeat a block of code multiple times, which makes your code shorter, cleaner, and easier to manage.  
The **`for` loop** is one of the most commonly used loop structures.

## 1. Basic syntax
```
for (initialization; condition; increment) {
  // code to be executed in each iteration
}
```
- **initialization**: Sets up a counter variable, usually starting at a specific value, e.g., `let i = 0`.
- **condition**: The loop will run as long as this is true, e.g., `i < 5`.
- **increment**: Updates the counter after each iteration, e.g., `i++` increases `i` by 1.
- **The body**: The block of code to run each time, wrapped in `{ }`.

**Example**:
```
for (let i = 0; i < 5; i++) {
  console.log("Iteration number: " + i);
}
```
> Tip: Always make sure your loop’s condition will eventually become false, or it will run forever.

---

## 2. Looping through an array
You can also use a `for` loop to go through each element of an array.

```
const fruits = ["Apple", "Banana", "Orange"];

for (let i = 0; i < fruits.length; i++) {
  console.log("Fruit: " + fruits[i]);
}
```

**Output**:
```
Fruit: Apple
Fruit: Banana
Fruit: Orange
```

---

## 3. Common use cases
For loops are often used for:
- Iterating over arrays
- Running code a fixed number of times
- Performing repeated calculations

For more about loops in JavaScript, check the MDN docs:  
[MDN for loop guide](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/for)
```

