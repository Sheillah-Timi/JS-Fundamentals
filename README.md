<<<<<<< HEAD
\## 📁 File: 1-multi\_languages.js



This script prints three lines using `console.log()`:





\### Concepts demonstrated:

\- Declaring multiple constants

\- Printing multiple lines using `console.log()`


=======
\# JS-Fundamentals



This project contains JavaScript scripts for learning core concepts.
>>>>>>> dff7665a466afb944ef71e4dad43147bea14628e

---

## 📁 File: 2-arguments.js

This script prints a message depending on the number of arguments passed via the command line:

- If no arguments → `No argument`
- If one argument → `Argument found`
- If more than one → `Arguments found`

### Concepts demonstrated:
- Using `process.argv`
- Conditional logic
- `console.log()` output
- No use of `var`

---

## 📁 File: 3-value_argument.js

This script prints the **first argument** passed to it.

- If no arguments → `No argument`
- If one argument → it prints that value

### Concepts demonstrated:
- Accessing specific CLI arguments (`process.argv[2]`)
- Avoids `.length`
- Uses `const` only


Examples:
- `node 4-concat.js c cool` → `c is cool`
- `node 4-concat.js c` → `c is undefined`
- `node 4-concat.js` → `undefined is undefined`

### Concepts demonstrated:
- Handling multiple CLI arguments
- Template literals
- No use of `var`
---

## 📁 File: 5-to_integer.js

This script checks if the first argument can be converted to an integer.

- If it can: prints `My number: <integer>`
- If not: prints `Not a number`

### Examples:
```bash
node 5-to_integer.js        → Not a number  
node 5-to_integer.js 89     → My number: 89  
node 5-to_integer.js "89"   → My number: 89  
node 5-to_integer.js 89.89  → My number: 89  
node 5-to_integer.js School → Not a number  
---

## 📁 File: 6-multi_languages_loop.js

This script prints 3 lines using an **array and a loop**, without `var` or `if/else`.

### Output:
---

## 📁 File: 7-multi_c.js

This script prints `"C is fun"` x times, where x is the first argument.

- If x is not a valid number → prints: `Missing number of occurrences`
- If x is valid and positive → prints `"C is fun"` that many times

### Examples:
```bash
node 7-multi_c.js       → Missing number of occurrences  
node 7-multi_c.js 2     → C is fun\nC is fun  
node 7-multi_c.js 5     → C is fun (x5)  
node 7-multi_c.js -3    → (prints nothing)  
---

## 📁 File: 8-square.js

This script prints a square of `X` characters based on the size from the first argument.

- If no argument or not a number → prints: `Missing size`
- If argument is a valid integer → prints a square

### Examples:
```bash
node 8-square.js       → Missing size  
node 8-square.js School→ Missing size  
node 8-square.js 2     → XX \n XX  
node 8-square.js 6     → XXXXXX (6x rows)  
