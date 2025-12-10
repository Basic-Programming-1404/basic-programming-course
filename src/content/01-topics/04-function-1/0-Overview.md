# 🧭 Topic: Function Basics

> [!info] **Quick Overview :**
> 
> This topic introduces functions in C++, why we use them, how they are
> defined and called, how parameters and return values work, and how to
> write clean, professional function-based code.

---
## 📌 Covered in This Topic

### **Introduction to Functions**
- What functions are (self-contained blocks of code)
- Key goals:
    - Modularity
    - Reusability (Write once, use everywhere)
    - Readability
    - Debugging & error isolation
- Real-world analogy: a “machine” that takes input and produces output

### **Why We Need Functions**
- Eliminating repetition (D.R.Y. — Don’t Repeat Yourself)
- Breaking problems into sub-problems
- Reducing complexity
- Abstraction (main doesn’t care *how*, only *what*)
- Professional collaboration benefits

### **User-Defined Functions**
- Anatomy of a function:
    - Return type
    - Function name
    - Parameters
    - Body
- Function lifecycle:
    - Declaration (prototype)
    - Definition
    - Calling
- Declaration vs. Definition
- Function prototypes and their purpose

### **Return Types**
- Allowed return types
- Limitation: a function returns only **one value**
- `void` functions:
    - Definition and use cases
    - Using `return;` as an “exit door”

### **Parameters & Arguments**
- Parameter vs. argument (placeholder vs. actual data)
- Order and clarity of parameters
- Parameter names optional in prototypes
- Scope and lifetime of parameters

### **Scope & Lifetime**
- Local variables
- Global variables:
    - What they are
    - Why to avoid them
- Static local variables
- Variable shadowing
- Priority of scopes

### **Default Arguments**
- Syntax of default parameters
- Rules:
    - Must be placed on the **right**
    - Evaluated at **compile time**
- Correct vs. incorrect usage
- Common ambiguity problems

### **Parameter Passing Methods**
- **Pass by value**
    - Copy is made
    - Original variable unchanged
    - Best for small data types
- **Pass by reference (`&`)**
    - Works on original variable
    - Used for modification or performance
- When and why to choose each method

### **Function Overloading**
- Definition of overloading
- Valid overloading rules
- Return type alone does NOT overload
- Overload resolution basics
- Numeric literal suffixes and their effect
- Overloading vs. default arguments (ambiguity)

### **Clean Code & Best Practices**
- Syntax and formatting
- Function placement & structure
- Meaningful naming (verbs for functions)
- SRP (Single Responsibility Principle)
- Function length and complexity
- Refactoring deeply nested logic

---
## 📑 Slides & Materials
- 👨‍🏫 [Professor Slides (PDF)](4-ProfessorSlides.md)  
- 🧑‍🏫 [TA Workshop Slides (PDF)](5-TASlides.md)

---
## 🛠️ Workshop & Assignments

- 💬 [Workshop Questions](01-topics/04-function-1/1-Workshop.md)
- 🧮 [Assignments](2-Assignment.md)
- ❓ [Q&A and Common Issues]()

---
## 🌐 Additional Resources
- C++ Reference (cplusplus.com)

---
## ⏩ Navigation

- ⬅️ [Previous Topic: Conditions & Loops](../03-conditions-loops/0-Overview.md)  
- ➡️ [Next Topic: Arrays](../05-arrays/0-Overview.md)
---

> [!tip] **Tip :**
> 
> If something doesn’t make sense — **don’t stay stuck alone**. Ask the TA to clarify it right away. Often, a quick question can save you a lot of time and frustration. Remember: if you’re confused, chances are others are too.

