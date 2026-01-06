# 🧭 Topic: Pointers

> [!info] **Quick Overview :** This topic covers how memory is accessed and managed in C++, starting from memory addresses and the address-of operator (`&`), and moving to pointers as variables that store addresses. It explains dereferencing, pointer arithmetic, pointer types (including `void*` and pointer-to-pointer), and why all pointers have the same size on a given architecture. The relationship between arrays and pointers is discussed, including common pitfalls when passing arrays to functions. The overview also contrasts stack and heap memory, introduces dynamic allocation with `new` and `delete`, and highlights common pointer errors such as wild and dangling pointers, variables going out of scope, and the use of `nullptr`. Finally, it clarifies the role of `const` with pointers, compares pointers with reference variables, and explains why pointers are used in functions for efficiency, output parameters, and managing dynamic memory.


## 📌 Covered in This Topic
- **Memory addresses**
    - What a memory address is and what it represents
- **The address-of operator (`&`)**
    - How `&` is used to obtain a variable’s address
- **Pointers**
    - What a pointer is
    - Pointer size (independent of the pointed type)
- **Wild pointers**
    - What they are and why they are dangerous
- **Raw pointers vs smart pointers (brief)**
    - Why raw pointers exist
    - A short mention of `unique_ptr`, `shared_ptr`, `weak_ptr`
- **Array names and pointers**
    - How array names decay to pointers
    - Problems when passing arrays to functions (loss of size information)
- **Dereferencing (`*`)**
    - Accessing the value a pointer points to
    - Using dereferencing to access array elements
- **Pointer arithmetic**
    - How incrementing/decrementing pointers works
    - Relation to the pointed data type
- **Size of pointers**
    - Why all pointers have the same size on a given architecture
- **Pointer data types**
    - Why pointers must have a data type
    - How the type affects dereferencing and arithmetic
- **Void pointers (`void*`)**
    - What they are
    - Limitations and use cases
- **Pointer to pointer**
    - Why and when double pointers are used
- **Stack vs heap**
    - Why the stack is not always sufficient
    - When dynamic (heap) allocation is required
- **Dynamic memory allocation**
    - `new` and `delete`
    - `new[]` and `delete[]`
- **Reference variables**
    - What references are
    - Differences between references and pointers
- **Dangling pointers**
    - How dangling pointers are created
    - How to avoid and handle them
- **`nullptr`**
    - Why it exists
    - Difference from `NULL` and `0`
- **Const and pointers**
    - `const int*`
    - `int* const`
    - `const int* const`
- **Variables going out of scope**
    - Lifetime of local variables
    - Effects on pointers and references
- **Pointers and functions**
    - Passing pointers to functions (input)
    - Returning pointers from functions (output)
    - Why pointers are used: efficiency, modification, dynamic memory, and shared data

---
## 📑 Slides & Materials
- 👨‍🏫 [Professor Slides (PDF)](01-topics/07-pointers/4-ProfessorSlides.md)
- 🧑‍🏫 [TA Workshop Slides (PDF)](01-topics/07-pointers/5-TASlides.md)

---
## 🛠️ Workshop & Assignments

- 🧮 [Assignments](01-topics/04-function-1/2-Assignment.md)
- ❓ [Q&A and Common Issues]()

---
## 🌐 Additional Resources


---
## ⏩ Navigation

- ⬅️ [Previous : Functions 2 - Recursion](../06-functions-2/0-Overview.md)
- ➡️ [Next Topic: File & Struct](../08-file-struct/0-Overview.md)


---

> [!tip] **Tip :**
> 
> If something doesn’t make sense — **don’t stay stuck alone**. Ask the TA to clarify it right away. Often, a quick question can save you a lot of time and frustration. Remember: if you’re confused, chances are others are too.

