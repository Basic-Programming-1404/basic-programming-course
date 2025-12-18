# 🧭 Topic: File & Struct

> [!info] **Quick Overview :** 


## 📌 Covered in This Topic
- **What is a `struct`?**
    - Grouping related variables under one name
    - Difference between separate variables vs a structured type
- **Why do we need structs?**
    - Modeling real-world entities (Student, Book, Point, Date, etc.)
    - Improving code readability and organization
    - Passing related data together to functions
- **Defining a struct**
    - Basic syntax
    - Declaring variables of a struct type
    - Accessing members using the `.` operator
- **Naming conventions**
    - Struct names (PascalCase or camelCase)
    - Member variable names (camelCase / snake_case)
- **Methods (functions) inside structs**
    - Member functions
    - Difference between data members and behavior
    - When logic belongs inside the struct vs outside
- **Constructors in structs**
    - Default constructor
    - Parameterized constructor
    - Initializing members properly
    - Why constructors are useful
- **Nested structs**
    - Structs inside other structs (composition)
    - Modeling “has-a” relationships
    - Why a struct **cannot contain itself by value**
        - Infinite size problem
    - Using pointers to the same struct type (`Node* next`)
- **Pointers to structs**
    - Creating structs on the heap using `new`
    - Accessing members with the `->` operator
    - Difference between `.` and `->`
    - Common mistakes (dangling pointers, forgetting `delete`)
- **Passing structs to functions**
    - By value
    - By reference
    - By pointer
    - Performance and safety considerations
- **Common examples and use cases**
    - Student records
    - Game objects
    - Linked list nodes
    - Configuration or settings data

- **Why do we need files?**
    - Data persistence (programs don’t lose data after closing)
    - Saving and loading program state
    - Working with large datasets
- **File streams and buffers**
    - `ifstream`, `ofstream`, `fstream`
    - How buffering works (conceptual overview)
    - Difference between console I/O and file I/O
- **Sequential File I/O**
    - Opening and closing files
        - File modes (`ios::in`, `ios::out`, `ios::app`, etc.)
    - Checking if a file is open
        - `is_open()` and error handling
    - Reading from files
        - `>>` operator
        - `getline()`
        - Reading line by line
    - Writing to files
        - Overwriting vs appending
        - Formatting output
- **Formatted I/O**
    - Using `setw()`, `left`, `right`, `setprecision`
    - Writing aligned and readable data to files
- **Converting file input**
    - Reading strings and converting to numbers
    - `stoi`, `stof`, `stod`, `stoll`
    - Handling invalid input safely
- **Error handling and debugging**
    - Using `cerr` for error messages
    - Checking stream state (`fail()`, `eof()`)
- **Reading structured data**
    - Reading struct data from files
    - Reading CSV-formatted files
        - Delimiters
        - Parsing lines manually
        - Common pitfalls
- **Random access File I/O**
    - Concept of file cursor
    - `seekg()` and `tellg()`
    - When random access is useful
    - Limitations and typical use cases


## 📑 Slides & Materials
- 👨‍🏫 [Professor Slides (PDF)](01-topics/07-pointers/4-ProfessorSlides.md)
- 🧑‍🏫 [TA Workshop Slides (PDF)](01-topics/07-pointers/5-TASlides.md)

---
## 🛠️ Workshop & Assignments

- 🧮 [Assignments](2-Assignment.md)
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

