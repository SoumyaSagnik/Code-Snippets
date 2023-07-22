# JavaScript Map

```javascript
const map = new Map();
map.set(1, "a");
map.set(2, "b");
console.log(map); // {1 => 'a', 2 => 'b'}

console.log(map.keys()); // {1, 2}
console.log(map.values()); // {'a', 'b'}

for (let [key, value] of map) {
  if (value === "a") console.log(key); // 1
}

console.log(map.get(1)); // a
```

---

# Removing falsy values from array

```javascript
const arr = [1, 0, null, "", undefined, false, -5];
console.log(arr.filter(Boolean)); // [1, -5]
```

# Printing variable name with value

```javascript
const a = 10;
console.log({ a }); // {a: 10}
```

---

# Round off number to a particular decimal point

```javascript
const n = 3.69;
console.log(n.toFixed(5)); // 3.690000
console.log(n.toFixed(1)); // 3.7
console.log(n.toFixed(0)); // 4
```

---
