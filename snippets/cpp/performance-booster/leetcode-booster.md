---
title: leetcode-booster
description: GCC optimizations and fast I/O techniques to reduce execution time and meet LeetCode time limits.
author: Mohamed-faaris
tags: cpp,optimization,leetcode,fast-io
---

```cpp
#pragma GCC optimize("O3,unroll-loops")
#pragma GCC target("avx2,bmi,bmi2,lzcnt,popcnt")

static const bool Booster = []() {
    std::ios_base::sync_with_stdio(false);
    std::cin.tie(nullptr);
    std::cout.tie(nullptr);
    return true;
}();
```
