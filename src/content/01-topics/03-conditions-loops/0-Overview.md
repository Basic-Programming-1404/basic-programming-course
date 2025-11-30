# 🧭 Topic: C++ Control Structures


> [!info] Quick Overview
> 

---
## 📌 Covered in This Topic

### Part 1 - Conditions
- Introduction to Control Structures
	- What are _control structures_ and why they matter
	- How conditions allow decision-making in programs
	- Types of control flow in C++:
	    - Sequential
	    - Selection (branching — **this lecture’s focus**)
	    - Iteration (to be covered later)
- 2. Operators and Their Categories
	- Overview: Operators as tools for computation and logic
	- Main categories relevant to conditions:
	    - **Arithmetic operators** (`+`, `-`, `*`, `/`, `%`) – for expressions inside conditions
	    - **Comparison / Relational operators** ` ==, !=, <, >, <=, >=`
    - Logical operators (`&&`, `||`, `!`)
    - Bitwise operators (intro only) (`&`, `|`, `^`, `~`, `<<`, `>>`)
        - Distinguish between _bitwise_ and _logical_ operations
        - Simple binary truth table demonstration

- Boolean Expressions and Truth Evaluation
	- How C++ evaluates boolean expressions (`true`, `false`, `0`, `non-zero`)
	- Short-circuit evaluation with `&&` and `||`
	- Expression combinations and nested conditions
	- Boolean variables and expressions (`bool is_valid = age > 18;`)
	
- Conditional Statements
	- The `if` Statement**
		- Basic syntax and flow
		- Single-statement vs block (`{}`) forms
		- Recommended: **always use braces** for clarity and safety
		- Readability and indentation rules
	- if...else` and `else if Chains
		- Multi-condition logic
		- Execution flow and exclusivity (only one branch executes)
		- Common pitfalls (missing `else`, overlapping conditions)
-  Nested `if` Statements
	- When to nest vs when to restructure
	- Clean and readable formatting examples
	- Introduce the idea of _early return_ or _guard clauses_ as clean code alternatives

- The Ternary Operator (`?:`)**
	- Syntax and usage
	- Example: `result = (x > 0) ? 1 : -1;`
	- When to use vs when not to use
	- _“Short-hand if”_ — only for **simple assignments or expressions**
	- Readability trade-offs

- The `switch` Statement
	- Purpose and syntax
	- Supported data types:
	    - `int`, `char`, `enum`, `bool` (and C++11 `constexpr` integral types)
	    - ⚠️ Not supported: `float`, `double`, `string`
- **Case labels** and the need for `break`
- **Default** case and its importance
- Fall-through behavior (intentional vs accidental)
- Example: menu-based program with `switch`

-  Operator Precedence and Associativity**
	- Order in which operators are evaluated
	- Why parentheses improve readability and prevent bugs
	- Quick reference table for comparison, logical, and arithmetic operators
	- Example comparisons showing subtle precedence mistakes

- Clean Code and Best Practices**
	- Always use braces `{}` even for single statements
	- Align and indent consistently
	- Use descriptive variable and condition names (`if (is_authenticated)` not `if (x)`)
	- Avoid deeply nested conditions (refactor with functions or early returns)
	- Comment _why_ not _what_
	- Test all branches (especially edge cases and default paths)

---
### Part 2 - Loops
- **Introduction to Iteration**
    - Why repetition is needed in programs
    - The concept of control flow — branching vs looping
- **The `while` Loop**
    - Syntax and structure
    - Flow of control in `while`
    - Typical use cases: input validation, sentinel-controlled loops
    - Common pitfalls (infinite loops, missing updates)
- **The `do-while` Loop**
    - Difference between `while` and `do-while` (post-test vs pre-test)
    - When to use `do-while` (menus, repeated input until valid)
- **The `for` Loop**
    - Syntax and structure (`initialization`, `condition`, `update`)
    - Iterating over numeric ranges
    - Loop variable scope and lifetime
    - Variations: multiple initializations, empty components
    - Using `for` for counting and fixed iterations
- **Loop Control Statements**
    - `break` — exiting early
    - `continue` — skipping to next iteration
    - `return` in loops
    - Discuss readability vs misuse of these
- **Nested Loops**
    - How inner loops behave relative to outer loops
    - Common examples: printing patterns, working with 2D arrays
    - Complexity growth and performance intuition (Brief)
- **Loop Design Patterns**
    - Counter-controlled loops
    - Sentinel-controlled loops
    - Flag-controlled loops
    - Infinite loops with `break` condition
- **Order of Execution Recap**
    - Loop initialization → condition check → body → update
    - Flow diagrams to illustrate control
- **Best Practices and Clean Code**
    - Avoid “magic numbers” — use constants in loop bounds
    - Use meaningful variable names (`i`, `j` are fine for indices, otherwise be descriptive)
    - Ensure loops have clear termination conditions
    - Maintain consistent indentation and brace style
- **Debugging and Tracing Loops**
    - Using print statements to track variables
    - Recognizing off-by-one errors

## 📑 Slides & Materials
- 👨‍🏫 [Professor Slides (PDF)](01-topics/03-conditions-loops/4-ProfessorSlides.md)
- 🧑‍🏫 [TA Workshop Slides (PDF)](01-topics/03-conditions-loops/5-TASlides.md)

---
## 🛠️ Workshop & Assignments

- 💬 [Workshop Questions](01-topics/01-problem-solving/2-Assignment.md)
- 🧮 [Assignments](01-topics/01-problem-solving/2-Assignment.md)
- ❓ [Q&A and Common Issues]()

---
## 🌐 Additional Resources

- [C++ Reference](https://cplusplus.com/reference/)  
- [Learn C++](https://www.learncpp.com/)  
- [Data Types in C++ (W3Schools)](https://www.w3schools.com/cpp/cpp_data_types.asp)

---
## ⏩ Navigation

- ⬅️ [Previous Topic: Basics and Data Types](../02-basics-and-data-types/0-Overview.md)  
- ➡️ [Next Topic: Functions 1](../04-function-1/0-Overview.md)
---

> [!tip] Tip
> If something doesn’t make sense — **don’t stay stuck alone**. Ask the TA to clarify it right away. Often, a quick question can save you a lot of time and frustration. Remember: if you’re confused, chances are others are too.

