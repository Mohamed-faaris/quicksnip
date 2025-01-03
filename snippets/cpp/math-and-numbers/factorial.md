---
title: Factorial
description: Calculate the factorial of an integer using a while loop
tags: math, factorial, loop
author: Mohamed-faaris
---

```cpp
int factorial(int n) {
    if (n < 0) throw std::invalid_argument("Factorial is not defined for negative numbers.");
    int result = 1;
    while (n > 1) {
        result *= n;
        n--;
    }
    return result;
}

// Usage:
factorial(5); // Returns: 120
```
