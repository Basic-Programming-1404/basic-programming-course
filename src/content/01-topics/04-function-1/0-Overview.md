# 🧭 Topic: Function Basics


> [!info] Quick Overview
> 

---
## 📌 Covered in This Topic

 **Introduction to Functions**
- What functions are
- Key goals: modularity, reuse, readability, debugging
- Real-world analogy: “tasks” or “machines” that take input and produce output

**Why We Need Functions**
- Code reuse
- Reducing complexity
- Avoiding repetition
- Breaking problems into sub-problems
- Making programs testable
- Collaboration benefits: multiple people working on different functions

**Predefined Library Functions**
- Overview of `<cmath>`, `<iomanip>`, helpers
- Calling library functions (syntax, examples)

**User-Defined Functions**
- Components of a user-defined function
- **Declaration** vs. **Definition** vs. **Call**
- Variables inside functions (local variables & scope)
- Global variables — why to avoid them
- Lifetime and visibility of variables

**Parameters, Arguments & Terminology**
- Parameter vs. Argument (definition, examples)
- Types of parameters: input, output, in-out
- Naming conventions for parameters
- Why parameter order and clarity matter
- Common student mistakes (e.g., confusing scope)

**Return Types**
- `void` vs. non-void
- Returning multiple values → reference parameters
- Return type limitations (only one return value)
- Allowed data types
- When to use `return;` in void functions
- Early returns and readability. (Guard Clause)

**Function Prototypes**
- What prototypes do
- Why prototypes are needed in C++
- Where to place prototypes (before `main` or in headers)
- Typical student errors (e.g., mismatched signatures)

**Default Arguments**
- Syntax for default values
- Rules (right-to-left, only in declaration)
- Good vs. bad use cases
- Common pitfalls

**Parameter Passing Methods**
- **Pass by value**
    - Cheap for ints, bools, chars
    - Safe, makes a copy
- **Pass by reference (`&`)**
    - Used for modifying caller variables
    - Used for performance
- **When to choose which method**
	- Memory model overview (stack frame, copies)


**Function Overloading**
- What overloading is
- Rules for valid overloading
- Overloading vs. default args and ambiguity
- Examples: `abs`, `sort`, etc.
- Common pitfalls (type conversion confusion)

**Clean Code & Best Practices**
**Syntax**
- Consistent formatting
- Clear parameter naming
- Avoid deeply nested logic inside functions

**Naming**
- Verbs for functions (`calculateTotal`, `isValid`)
- Avoid generic names (`func1`, `doStuff`)
- Self-documenting naming

**SRP (Single Responsibility Principle)**
- One function should do one thing
- How complex is “too complex”?
- When to break a function into smaller pieces

**Function Length & Complexity**
- Cyclomatic complexity
- Indicators that a function needs refactoring
- How to make logic testable

**Scope, Lifetime & Static Functions**
- Local vs. global variables
- Shadowing
- `static` local variables
- When to use function-level statics
- Danger of relying on state

**Common Student Mistakes**
- Defining a function inside another function
- Forgetting to return a value
- Mismatched declaration and definition
- Depending on global variables instead of parameters
- (Optional) Passing large objects by value

---

## 📑 Slides & Materials
- 👨‍🏫 [Professor Slides (PDF)](01-topics/04-function-1/4-ProfessorSlides.md)  
- 🧑‍🏫 [TA Workshop Slides (PDF)](01-topics/04-function-1/5-TASlides.md)

---
## 🛠️ Workshop & Assignments

- 💬 [Workshop Questions](01-topics/04-function-1/2-Assignment.md)
- 🧮 [Assignments](01-topics/04-function-1/2-Assignment.md)
- ❓ [Q&A and Common Issues]()

---
## 🌐 Additional Resources

- [C++ Reference](https://cplusplus.com/reference/)  

---
## ⏩ Navigation

- ⬅️ [Previous Topic: Conditions & Loops](../03-conditions-loops/0-Overview.md)  
- ➡️ [Next Topic: Arrays](../05-arrays/0-Overview.md)
---

> [!tip] Tip
> If something doesn’t make sense — **don’t stay stuck alone**. Ask the TA to clarify it right away. Often, a quick question can save you a lot of time and frustration. Remember: if you’re confused, chances are others are too.

