
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

> **Note on Viewing PDFs on GitHub:**  
> If you encounter an "Unable to render code block" or preview error when opening a **📄 View PDF on GitHub** link, please reload the page or use the **⬇️ Download PDF** link right below it.

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
| Topics Covered | Page |
| :--- | :--- |
| File handling: purpose (read from and write to files) | `page 1` |
| Opening a file: open(filename, mode) | `page 1` |
| Common modes: r, w, a, b, x (exclusive creation), + (update) | `page 1` |
| Reading a file: read() (entire file as a string) | `page 2` |
| readline() (one line at a time) | `page 2` |
| readlines() (all lines into a list) | `page 2` |
| Iterating over lines with a for loop and strip() | `page 2` |
| Writing to a file: write() | `page 3` |
| writelines() (a list of strings) | `page 3` |
| Using with for file handling (file closes automatically, even on an exception) | `page 3` |
| Binary files (rb / wb, copying image.png) | `page 4` |
| JSON: reading with json.load() | `page 4` |
| JSON: writing with json.dump() | `page 4` |
| CSV: reading with csv.reader | `page 5` |
| CSV: writing with csv.writer and writerows() | `page 5` |
| Pickle: definition (serialize and deserialize Python objects) | `page 5` |
| Pickle: writing with pickle.dump() | `page 5` |
| Pickle: reading with pickle.load() | `page 5–6` |
| End of the pickle read example (print(data)) | `page 6` |
- [📄 View PDF on GitHub](https://github.com/DhawaDG/Python_fundaments/blob/main/filehandling.pdf)
- [⬇️ Download PDF](https://github.com/DhawaDG/Python_fundaments/raw/refs/heads/main/filehandling.pdf)

### 6. Object-Oriented Programming (OOP)
| Topics Covered | Page |
| :--- | :--- |
| Classes: blueprint definition, Dog example (attributes and a method) | `page 1` |
| Constructors: definition, init, and the default constructor | `page 1` |
| Parameterized constructor | `page 2` |
| Non-parameterized constructor | `page 2` |
| Key concepts: the self parameter | `page 2` |
| Initialization, custom arguments, default values | `page 3` |
| Advanced constructor concepts: constructor overloading (default args, *args, **kwargs) | `page 4` |
| Dynamic attributes with setattr() | `page 4–5` |
| Calling other methods from the constructor | `page 5` |
| Destructors (del) | `page 5` |
| Constructor chaining with super() | `page 6` |
| Objects (multiple objects from one class) | `page 7` |
| Inheritance: definition, Animal and Dog example | `page 7–8` |
| Types of inheritance: single, multiple | `page 8` |
| Multilevel and hierarchical inheritance | `page 9` |
| Hybrid inheritance | `page 10` |
| Method overriding | `page 10` |
| Access modifiers: public in inheritance | `page 11` |
| Protected in inheritance () | `page 11–12` |
| Private in inheritance (__), name mangling | `page 12` |
| Encapsulation: definition, private members, BankAccount example | `page 13` |
| Using BankAccount, name-mangled access, whether get methods are compulsory | `page 14` |
| Protected members (Person and Student) | `page 15–16` |
| Student object output, why display(self) needs no parameters | `page 17` |
| What super() does, and that the rule is the same for public, protected and private | `page 17` |
| Public members (Car example) | `page 18` |
| Getters and setters (@property, @celsius.setter, Temperature example) | `page 19` |
| Getter vs setter comparison table | `page 20` |
| Abstraction: definition, car analogy, ABC and @abstractmethod | `page 21–22` |
| Abstract class Car, subclasses ElectricCar and PetrolCar, example output | `page 21–23` |
| Subclass method names must match the abstract method | `page 24` |
| Abstraction vs encapsulation table | `page 24` |
| Why super() is needed: to call the parent constructor (with and without super()) | `page 25–26` |
| Why super() is needed: to extend parent class methods | `page 27` |
| Why super() is needed: to handle multiple inheritance (MRO, classes A, B, C, D) | `page 28–29` |
| super() vs return in start_engine | `page 29, 31` |
| Why you don’t need super() to access self.name | `page 30` |
| When you need super(); what return does | `page 31` |
| Conceptual questions: why override the constructor and call super() | `page 32–33` |
| Modifying parent class attributes in the child | `page 33` |
| Preventing direct instantiation of an abstract parent (TypeError) | `page 33–34` |
| Polymorphism: definition | `page 35` |
| Method overriding with abstract base classes (Animal, Dog, Cat) | `page 35` |
| Objects in a list, calling the same method on each | `page 35–36` |
| “What is an object and its data type?” (everything is an object) | `page 36–37` |
| Method overloading (not directly supported in Python) | `page 37` |
| Duck typing (make_sound) | `page 38` |
| Class, object, method and function relationship diagram | `page 39` |
| Abstract base classes (ABCs) | `page 39` |
| Types of polymorphism: compile-time (static) and run-time (dynamic) | `page 39` |

- [📄 View PDF on GitHub](https://github.com/DhawaDG/Python_fundaments/blob/main/OOP.pdf)
- [⬇️ Download PDF](https://github.com/DhawaDG/Python_fundaments/raw/refs/heads/main/OOP.pdf)



### 7. Modules and Packages
| Topics Covered | Page |
| :--- | :--- |
| What is a module (math_operations.py with add and subtract) | `page 1` |
| Importing modules (import module_name, module.function()) | `page 1` |
| Importing specific items (from module import item) | `page 2` |
| Importing all items (from module import *) | `page 2` |
| What is a package, and its directory structure (with a subpackage) | `page 3` |
| Importing from packages | `page 3` |
| Relative imports (from . import, from .subpackage import) | `page 3` |
| The init.py file: purpose (marks a directory as a package) | `page 4` |
| Why init.py matters (package marker, initialization code, controls imports) | `page 4` |
| Empty init.py | `page 4–5` |
| Non-empty init.py (runs initialization code, imports specific functions) | `page 5` |
| init.py with all (controls what from package import * imports) | `page 5–6` |
| Installing third-party packages (pip install requests, requests.get) | `page 6` |
- [📄 View PDF on GitHub](https://github.com/DhawaDG/Python_fundaments/blob/main/modelandpackages.pdf)
- [⬇️ Download PDF](https://github.com/DhawaDG/Python_fundaments/raw/refs/heads/main/modelandpackages.pdf)

### 8. Advanced Data Structures
| Topics Covered | Page |
| :--- | :--- |
| Stacks: LIFO definition, push, pop, peek, isEmpty | `page 1` |
| Implementing a stack in Python | `page 1–2` |
| Queues: FIFO definition, enqueue, dequeue, peek, isEmpty | `page 2` |
| Implementing a queue with deque (append, popleft) | `page 2–3` |
| Why use deque() and not a list for a queue | `page 3` |
| Linked lists: definition, singly vs doubly linked | `page 4` |
| Node class and LinkedList class code | `page 4–5` |
| print_list method and creating a linked list | `page 5` |
| Node class explained: data, next, self, self.data = data | `page 5–6` |
| How Node(10) works | `page 6–7` |
| LinkedList class overview: append() and print_list() | `page 7` |
| append() step 1: creating the new node | `page 7` |
| append() step 2: empty-list check and what self.head stores | `page 7–8` |
| Constructor attributes can be any data type | `page 8` |
| Composition vs inheritance (LinkedList uses Node) | `page 9` |
| What a Node object is, and how it looks in memory | `page 9` |
| self.head stores a reference to new_node | `page 10` |
| return after setting the head | `page 10` |
| Traversing to the end: last_node = self.head and the while last_node.next loop | `page 10–11` |
| Stop condition and the appending step last_node.next = new_node | `page 11–12` |
| print_list purpose and step-by-step (current, while loop, end=" -> ") | `page 12–14` |
| Printing None at the end of the list | `page 14` |
| Dry run of append(1) (empty list, return) | `page 14–15` |
| Dry run of append(2) and append(3) | `page 15–16` |
| Relation between LinkedList and print_list (heading only) | `page 16` |
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
