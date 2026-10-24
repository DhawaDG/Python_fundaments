
# Python Fundamentals: From Basics to Advanced Concepts

This repository documents my journey in mastering Python fundamentals. It includes projects and notes that demonstrate a solid understanding of core programming principles, essential for careers in data science, software development, and automation. The guided learning path has equipped me to write clean, efficient, and well-structured Python code.

---

## Hands-on Projects

| SN | Python Fundamentals Projects |
|:---:|:---|
| 1 | **[PassWord Manager System](https://github.com/DhawaDG/Password_Manager_Python)** |
| 2 | **[Expense Tracking System](https://github.com/DhawaDG/Expense_Tracker_System)** |

---

## Topics Covered

- **Python Basics:** Variables, data types, loops, conditionals (15h)
- **Functions & Modules:** (10h)
- **Data Structures:** Lists, Tuples, Sets, Dictionaries (15h)
- **File Handling:** open/read/write (8h)
- **Error Handling:** try-except (6h)
- **Object-Oriented Programming (OOP):** (20h)
- **Working with Libraries:** math, os, datetime (12h)
- **Lambda, List Comprehensions:** (10h)
- **Basic Unit Testing:** with assert or pytest (14h)
- **Decorators and Generators:** (10h)

---

# 📚 Python Fundamentals — Handwritten Notes PDF

A collection of detailed handwritten notes covering essential Python programming concepts, with explanations and summaries to support learning and revision.

## 📖 Handwritten Notes

### 1. Loops & Conditional Statements
| Topics Covered | Page |
| :--- | :--- |
| Control statements: flowchart “what to do if it is raining” | `page 1` |
| Flowchart symbols (rounded rectangle = start/end, diamond = branch, rectangle = other steps) | `page 1` |
| Elements of flow control: conditions (Boolean expressions) and clauses (blocks of code) | `page 2` |
| if statement: example (if name == 'Alice') and flowchart | `page 2` |
| else statement: example (Hi, Alice / Hello, stranger) and flowchart | `page 3` |
| elif statement: example (age < 12) and flowchart | `page 4` |
| while loop statement: if vs while code with spam < 5 | `page 5` |
| while loop flowchart | `page 5–6` |
| What happens in if and in while (step-by-step explanation) | `page 6` |
| if vs while comparison (runs once vs repeats) with sample output | `page 7` |
| break statement: while True loop asking for a name | `page 8` |
| break flowchart | `page 8` |
| continue statement: while True login example (name check, then password swordfish) | `page 9` |
| continue flowchart | `page 9–10` |
| End of the continue flowchart (print('Access granted'), End) | `page 10` |
- [📄 View PDF on GitHub](https://github.com/DhawaDG/Python_fundaments/blob/main/pythonconditionalstatement.pdf)
- [⬇️ Download PDF](https://github.com/DhawaDG/Python_fundaments/raw/refs/heads/main/pythonconditionalstatement.pdf)

### 2. Functions and Their Types
| Topics Covered | Page |
| :--- | :--- |
| Parameters vs arguments (multiply(x, y) example) | `page 1` |
| return statement (any data type, returns None if missing, square(n) example) | `page 1` |
| Default arguments (greet(name="Guest")) | `page 2` |
| Keyword arguments (describe_pet(name=..., animal=...)) | `page 2` |
| Positional arguments: args (sum_all) | `page 2` |
| **kwargs (describe(name="Alice", age=25)) | `page 2–3` |
| Lambda functions: definition and square example | `page 3` |
| Scope of variables: local vs global, global keyword (update_x) | `page 3` |
| Recursion (factorial(5) outputs 120) | `page 4` |
| Docstrings and help(add) | `page 4` |
| Lambda with multiple arguments (multiply = lambda x, y: xy) | `page 5` |
| Lambda with no argument (greet = lambda: "Hello, World!") | `page 5` |
| Lambda with built-in functions: map() (double a list) | `page 5` |
| Lambda with filter() (even numbers) | `page 5` |
| Lambda with sorted() using key | `page 5` |
- [📄 View PDF on GitHub](https://github.com/DhawaDG/Python_fundaments/blob/main/Functionsanditstypes.pdf)
- [⬇️ Download PDF](https://github.com/DhawaDG/Python_fundaments/raw/refs/heads/main/Functionsanditstypes.pdf)

### 3. Error Handling
| Topics Covered | Page |
| :--- | :--- |
| Error handling: purpose (handle errors gracefully instead of crashing) | `page 1` |
| try block (runs the code, except is skipped if no error) | `page 1` |
| except block (runs when an error occurs in try) | `page 1` |
| Uses: preventing crashes, graceful error handling, debugging | `page 1` |
| Syntax: try: / except ErrorType: | `page 1` |
| Common error types: ValueError (e.g. int("hello")) | `page 2` |
| ZeroDivisionError (e.g. 10/0) | `page 2` |
| TypeError (e.g. "hello" + 5) | `page 2` |
| FileNotFoundError (opening a file that doesn’t exist) | `page 2` |
| IndexError (e.g. my_list[10]) | `page 2` |
| finally block (always runs, useful for cleanup such as closing files) | `page 2` |
| Full example: try / except ValueError / except ZeroDivisionError / else / finally (10 divided by user input) | `page 3` |
- [📄 View PDF on GitHub](https://github.com/DhawaDG/Python_fundaments/blob/main/errorhandling.pdf)
- [⬇️ Download PDF](https://github.com/DhawaDG/Python_fundaments/raw/refs/heads/main/errorhandling.pdf)

### 4. Data Structures & Comprehensions
| Topics Covered | Page |
| :--- | :--- |
| Lists: properties (mutable, ordered, heterogeneous, indexed, dynamic) | `page 1` |
| Accessing list items: positive indexing, negative indexing, slicing | `page 1` |
| Modifying lists: changing an item | `page 1` |
| Adding items: append(), insert(), extend() | `page 1` |
| Removing items: remove(), pop(), del, clear() | `page 2` |
| List methods table (append, insert, extend, remove, pop, clear, index) | `page 2` |
| List methods continued (count, sort, reverse, copy) | `page 3` |
| List operations: concatenation, repetition, membership | `page 3` |
| List comprehension: syntax, the parts (expression, item, iterable, condition) | `page 4` |
| List comprehension examples: squares, uppercase strings, even numbers, words longer than 5 characters | `page 4` |
| Nested list comprehension (flattening a matrix) | `page 5` |
| Extracting keys from a dictionary | `page 5` |
| Replacing negative numbers | `page 5` |
| Tuples: properties (immutable, ordered, heterogeneous, indexed, hashable) | `page 6` |
| Converting a list to a tuple, single-item tuple, tuple without parentheses | `page 6` |
| Tuple indexing (positive, negative) and slicing | `page 6` |
| Immutability of tuples, and modifying by slicing and concatenating | `page 7` |
| Tuple operations: concatenation, repetition, membership | `page 7` |
| Multi-dimensional tuple | `page 8` |
| Unpacking tuples, and extended unpacking (a, *b = fruits) | `page 8` |
| Tuple methods (count, index) | `page 8` |
| Sets: properties (unique, unordered, mutable, fast membership, heterogeneous) | `page 9` |
| set() constructor, empty set, accessing items with in | `page 9` |
| Modifying sets: add(), update() | `page 9` |
| Removing items: remove(), discard(), pop(), clear() | `page 10` |
| Set operations: union, intersection, difference, symmetric difference | `page 10` |
| Frozen sets (frozenset) | `page 10` |
| Set methods list (including issubset, issuperset, isdisjoint) | `page 11` |
| Dictionaries: properties (key-value pairs, unordered, mutable, fast lookups) | `page 12` |
| Creating dictionaries: dict() constructor, from a list of tuples, empty dictionary | `page 12` |
| Accessing items: square brackets and get() with a default value | `page 12` |
| Adding or updating items | `page 12` |
| Removing items: pop(), popitem(), del, clear() | `page 13` |
| Dictionary operations: membership, length, iterating over keys, values and items | `page 13` |
| Nested dictionaries | `page 13` |
| Dictionary methods list | `page 14` |
| Dictionary comprehensions: syntax, squares, uppercase keys | `page 15` |
| Dictionary comprehensions with conditions (even squares, long words) | `page 15` |
| Matrix to dictionary | `page 16–17` |
| Applying a function to each value (abs) | `page 16–17` |
| Optional: building a dictionary with a for loop | `page 16–17` |

- [📄 View PDF on GitHub](https://github.com/DhawaDG/Python_fundaments/blob/main/datastructure.pdf)
- [⬇️ Download PDF](https://github.com/DhawaDG/Python_fundaments/raw/refs/heads/main/datastructure.pdf)

### 5. File Handling
- [📄 View PDF on GitHub](https://github.com/DhawaDG/Python_fundaments/blob/main/filehandling.pdf)
- [⬇️ Download PDF](https://github.com/DhawaDG/Python_fundaments/raw/refs/heads/main/filehandling.pdf)

### 6. Object-Oriented Programming (OOP)
Topics covered:
- Classes and Objects
- Constructors
- Inheritance and Its Types
- Method Overriding
- Access Modifiers
- Encapsulation and Abstraction
- Understanding `super()`
- Getters and Setters
- Polymorphism

- [📄 View PDF on GitHub](https://github.com/DhawaDG/Python_fundaments/blob/main/OOP.pdf)
- [⬇️ Download PDF](https://github.com/DhawaDG/Python_fundaments/raw/refs/heads/main/OOP.pdf)



### 7. Modules and Packages
- [📄 View PDF on GitHub](https://github.com/DhawaDG/Python_fundaments/blob/main/modelandpackages.pdf)
- [⬇️ Download PDF](https://github.com/DhawaDG/Python_fundaments/raw/refs/heads/main/modelandpackages.pdf)

### 8. Advanced Data Structures
Topics covered:
- Stacks
- Queues
- Linked Lists
- [📄 View PDF on GitHub](https://github.com/DhawaDG/Python_fundaments/blob/main/advanceddatastructure.pdf)
- [⬇️ Download PDF](https://github.com/DhawaDG/Python_fundaments/raw/refs/heads/main/advanceddatastructure.pdf)

### 9. Expense Tracker Project Explained
- The notes explain how the statement expenses = load_expenses_from_file() works by calling a function that returns a list of expenses and assigns that returned value to the variable.
- They illustrate newline escape sequences using examples like print("Hello \n World") to demonstrate how newline characters affect text output.
- They explain the role of the return statement within functions such as view-expenses(), showing that it terminates function execution immediately, provides an early exit when no expenses are present, and optionally sends results back to the caller.
- They cover the mechanics of enumerate(expanses, start=1) to show how loop iteration tracks both indices—starting from 1 instead of 0—and dictionary values through tuple unpacking, noting that the pipe symbol (|) serves purely as a visual separator for clarity.
- They clarify why file-handler.py contains two return statements, where return json.load(file) handles successful data loading and return [] provides a default empty list during error cases such as FileNotFoundError or JSONDecodeError.   

- [📄 View PDF on GitHub](https://github.com/DhawaDG/Python_fundaments/blob/main/Expemse_tracker.pdf)
- [⬇️ Download PDF](https://github.com/DhawaDG/Python_fundaments/raw/refs/heads/main/Expemse_tracker.pdf)

### 10. Password Manager Project Explained
- The notes explain the purpose of the strip() method in removing leading and trailing whitespace, tabs, and newlines from user input to prevent saving or comparison issues.
- They break down what .replace("", "").isalpha() does, showing that it first removes all spaces from a string and then checks if the remaining characters are strictly alphabetic.
- They cover how expressions like any(char in special_chars for char in user_password) iterate through a password string to verify the presence of required special characters.
- They detail how "".join(random.choice(all_chars) for _ in range(password_length)) works, explaining random.choice(), throwaway loop variables (_), loops, and string joining.
- They contrast the behavior of break, continue, and return statements in Python control flow.
- They explain why an item can still be accessed and printed after being removed via passwords.remove(queryname), detailing Python's reference-counting mechanism and how local variables maintain references in memory until they go out of scope.
  
- [📄 View PDF on GitHub](https://github.com/DhawaDG/Python_fundaments/blob/main/passwordmanager.pdf)
- [⬇️ Download PDF](https://github.com/DhawaDG/Python_fundaments/raw/refs/heads/main/passwordmanager.pdf)

---

## 💡 How to Use These Notes

- **View Online:** Click the View PDF on GitHub link to open the PDF file page.
- **Download:** Click the Download PDF link to access the original PDF file.
- **Study:** Use these notes for learning, practice, and revision of Python fundamentals.



---

## Book References

Key resources used during my learning journey:

- *Automate the Boring Stuff with Python* by Al Sweigart
- *Python Crash Course* by Eric Matthes
- *Fluent Python* by Luciano Ramalho
---

## ⬅️⬅️ [Back to Main Profile](https://github.com/DhawaDG)
