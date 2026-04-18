# Debounce Utility

## 📌 Problem
When a function is triggered frequently (e.g., typing in search input), it can cause performance issues.

## 💡 Solution
Debounce delays execution until the user stops triggering the function.

## ✅ Implementation
```js
import { debounce } from "./index.js";

const handleSearch = debounce((value) => {
  console.log("Searching for:", value);
}, 300);