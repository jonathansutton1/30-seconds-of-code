---
title: Number is multiple
tags: math, numbers
expertise: beginner
firstSeen: 2022-10-25T11:00:00-04:00
---

Checks if the second number is a multiple by the first.

- Use `Math.round()` to get an aproximation for very small numbers.
- Use the divisor `/` operator to check if the division operation results in the first number.

```js
const isMultiple = (x, y) => {
    return Math.round(x / y) / (1 / y) === x;
}
```

```js
isMultiple(10,20)  //true
```