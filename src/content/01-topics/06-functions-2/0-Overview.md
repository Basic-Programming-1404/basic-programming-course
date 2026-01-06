# 🧭 Topic: Recursive Functions

> [!info] **Quick Overview :**
>Recursion is a technique where a function solves a problem by calling itself on a smaller version of that problem, using a base case to stop the process. It’s useful for naturally hierarchical tasks like divide-and-conquer algorithms, backtracking, and tree or graph traversal. While recursion can make code simpler and more intuitive, it also uses more memory and can cause stack overflows if not designed carefully. Choosing recursion vs. iteration depends on the problem’s structure, performance needs, and clarity of the solution. 

## 📌 Covered in This Topic
- **1. Introduction to Recursion**
    - What recursion means (functions calling themselves)
    - Real-life analogy (matryoshka dolls / repeated tasks)
    - Structure of every recursive function (base case + recursive case)
- **2. How Recursive Functions Are Created**
    - Function call stack review (activation records, return addresses, parameters)
    - Base cases: preventing infinite recursion
    - Progress toward the base case (reducing the problem size)
    - Tracing a simple example (factorial, Fibonacci)
- **3. Relationship Between Recursion and Iteration**
    - Any recursive solution can be rewritten using loops
    - Recursion as a conceptual tool vs. iteration as a control-flow tool
    - Examples:
        - fibonacci (recursive → iterative)
        - factorial (recursive → iterative)
    - When compilers internally convert tail recursion to loops
- **4. Why Use Recursion? — Problems and Use Cases**
    - Problems naturally defined in terms of smaller subproblems
    - Divide-and-Conquer algorithms (Merge Sort, Quick Sort)
    - Backtracking problems (N-Queens, maze solving, subsets/permutations)
    - Tree/graph traversal (DFS)
    - Mathematical sequences (Fibonacci, exponentiation)
- **5. How to Choose Between Recursion and Iteration**
    - Use recursion when the problem is hierarchical, branching, or naturally recursive
    - Use iteration when performance and memory are critical
    - Avoid recursion when depth may be very large (risk of stack overflow)
    - Consider readability vs. efficiency trade-offs
- **6. Problems With Recursion**
    - High memory usage: stack frames
    - Stack overflow (deep recursion)
    - Re-computation of subproblems (e.g., naive Fibonacci)
    - Harder to debug for beginners
    - Function call overhead
- **7. Solutions and Optimizations**
    - **Tail Recursion**
        - What tail recursion is
        - How compilers can optimize it
        - Example of turning a normal recursion into tail recursion
    - **Memoization**
        - Caching results of recursive calls
        - When to use it (DP top-down)
        - Example: optimized Fibonacci
- **8. Worked Examples**
    - **N-Queens** (backtracking)
    - **Merge Sort** (divide-and-conquer)
    - **Tail-recursive factorial**
    - **Memoized Fibonacci**

---
## 📑 Slides & Materials
- 🧑‍🏫 [TA Workshop Slides (PDF)](01-topics/06-functions-2/5-TASlides.md)

---
## 🛠️ Workshop & Assignments

- 💬 [Workshop Questions](01-topics/05-arrays/1-Workshop.md)
- 🧮 [Assignments](01-topics/04-function-1/2-Assignment.md)
- ❓ [Q&A and Common Issues]()

---
## 🌐 Additional Resources
- C++ Reference (cplusplus.com)

---
## ⏩ Navigation

- ⬅️ [Previous : Arrays](../05-arrays/0-Overview.md)
- ➡️ [Next Topic: Pointers](../07-pointers/0-Overview.md)

---

> [!tip] **Tip :**
> 
> If something doesn’t make sense — **don’t stay stuck alone**. Ask the TA to clarify it right away. Often, a quick question can save you a lot of time and frustration. Remember: if you’re confused, chances are others are too.

