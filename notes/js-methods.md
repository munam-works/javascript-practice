# JS Methods Cheatsheet

Quick reference for stuff I learn. Format: method — what it does — example.

## Strings

### .trim()
Removes whitespace from both ends of a string (not the middle).
```js
"  hello world  ".trim(); // "hello world"
```

### .trimStart() / .trimEnd()
Same as trim() but only one side.
```js
"  hello  ".trimStart(); // "hello  "
"  hello  ".trimEnd();   // "  hello"
```
