
# 🧭 Topic: Arrays


> [!info] Quick Overview
> 

---
## 📌 Covered in This Topic

- Introduction to arrays
    - What arrays are at a conceptual level
    - Why we need them for grouped storage and efficient access
    - Arrays as contiguous blocks of memory
- Why array indices start at zero
    - Pointer + offset reasoning
    - Historical and implementation background
- Variable Length Arrays (VLAs)
    - What they are
    - Why they were removed from standard C++
    - Summary of compiler behavior and portability issues
- Declaring static arrays
    - Fixed-size nature
    - Examples of valid declarations
- Initialization techniques
    - Default initialization
    - Partial initialization
    - Aggregate initialization
    - Examples:
        - `int arr0[4] {};`
        - `int arr1[4] {1};`
- Accessing elements
    - Subscript operator usage
    - Input/output rules
    - Why the following fail:
        - `arr0 = arr1;`
        - `cin >> firstArr;`
        - `cout << firstArr;`
- Index out-of-bounds and undefined behavior
    - No boundary checking in C++
    - Overwriting other memory
    - Dangerous cases and debugging difficulty
- How arrays are stored in memory
    - Contiguous memory layout
    - Relationship to pointers
    - Implicit decay to pointer in expressions
- Using `sizeof` with arrays
    - Getting total size in bytes
    - Getting number of elements
    - Why `sizeof` gives different results inside functions
- Multidimensional arrays
    - Declaration of 2D and 3D arrays
    - Row-major order
    - Access patterns and common mistakes
- Passing arrays to functions
    - Array-to-pointer decay
    - Why arrays behave like pass-by-reference
    - Why arrays cannot be returned as raw types
    - Correct alternatives for returning array-like structures
- Returning arrays from functions (workarounds)
    - Returning pointers(will be covered later)
    - Returning structs
    - Using `std::array` or `std::vector` (future topic)
- Range-based for (`foreach`) loops with arrays
    - Syntax
    - Under-the-hood mechanics
    - When it can and cannot be used
- Teaser for dynamic arrays
    - Limitations of static arrays
    - Motivation for `new[]`, `delete[]`
    - Transition toward `std::vector` and dynamic memory in later topics
- C-style strings
    - Character arrays with `'\0'` termination
    - How they differ from `std::string`
    - Basic operations and pitfalls
- **C++ `std::string`**
	- Introduction to the `std::string` class
	- Why strings are safer than C-style arrays
	- Common operations:
	    - `.length()` / `.size()`
	    - `.empty()`
	    - `.substr()`
	    - `.find()`
	    - `.compare()`
	    - `.append()` / `+` concatenation
	    - `operator[]` for access
	- Input/output with strings
	- Mutability and memory handling differences compared to arrays 
---
## 📑 Slides & Materials

- 👨‍🏫 [Professor Slides (PDF)](01-topics/05-arrays/4-ProfessorSlides.md)
- 🧑‍🏫 [TA Workshop Slides (PDF)](01-topics/05-arrays/5-TASlides.md)

---
## 🛠️ Workshop & Assignments

- 💬 [Workshop Questions](1-Workshop.md)
- 🧮 [Assignments]()
- ❓ [Q&A and Common Issues]()

---
## 🌐 Additional Resources



---
## ⏩ Navigation

- ⬅️ [Previous Topic: Functions 1]()  
- ➡️ [Next Topic: Functions 2]()
---

> [!tip] Tip
> If something doesn’t make sense — **don’t stay stuck alone**. Ask the TA to clarify it right away. Often, a quick question can save you a lot of time and frustration. Remember: if you’re confused, chances are others are too.

