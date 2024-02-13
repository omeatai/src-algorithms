# src-algorithms

+CODEWARS

<details>
<summary>1. Multiples of 3 or 5 </summary>

# Multiples of 3 or 5

DESCRIPTION:

If we list all the natural numbers below 10 that are multiples of 3 or 5, we get 3, 5, 6 and 9. The sum of these multiples is 23.

Finish the solution so that it returns the sum of all the multiples of 3 or 5 below the number passed in.

Additionally, if the number is negative, return 0.

Note: If the number is a multiple of both 3 and 5, only count it once.

### PYTHON SOLUTION:

```py
 def solution(number):
    return sum(x for x in range(number) if x % 3 == 0 or x % 5 == 0)
```

```py
def solution(number):
    threes = list(range(3, number, 3))
    fives = list(range(5, number, 5))
    return sum(list(set(threes + fives)))
```

```py
def solution(number):
    sum = 0
    for i in range(number):
        if (i % 3) == 0 or (i % 5) == 0:
            sum += i
    return sum
```

### JAVASCRIPT SOLUTION:

```js
function solution(number) {
  let total = 0;
  for (let i = 0; i < number; i++) {
    if (i % 3 === 0 || i % 5 === 0) {
      total += i;
    }
  }
  return total;
}
```

```js
function solution(number) {
  return number < 1
    ? 0
    : [...new Array(number).keys()]
        .filter((n) => n % 3 == 0 || n % 5 == 0)
        .reduce((a, b) => a + b);
}
```

# #END</details>

<details>
<summary>2. Data Type - String </summary>

# Data Type - String

### PYTHON SOLUTION:

```py

```

```py

```

```py

```

### JAVASCRIPT SOLUTION:

```py

```

```py

```

```py

```

```py

```

```py

```

```py

```

```py

```

```py

```

```py

```

```py

```

```py

```

```py

```

```py

```

```py

```

```py

```

```py

```

```py

```

```py

```

```py

```

```py

```

```py

```

# #END</details>
