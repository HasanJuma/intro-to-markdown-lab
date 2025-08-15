# The for Loop in JavaScript
![header image](https://images.unsplash.com/photo-1515879218367-8466d910aaa4?q=80&w=2069&auto=format&fit=crop&ixlib=rb-4.0.3)

The for loop in JavaScript is used to repeat a block of code a set number of times.

## 1. Basic syntax

```javascript
for (initialization; condition; finalExpression) {
  // code to be executed in each loop iteration
}

initialization: runs once before the loop starts (e.g., let i = 0).

condition: checked before each iteration; if true, the loop continues.

finalExpression: executed after each iteration (e.g., i++ to increment).

body: the block of code to execute.


Example:

for (let i = 1; i <= 5; i++) {
  console.log(i);
}
// Output: 1 2 3 4 5

For more details, check MDN – Loops and iteration.
