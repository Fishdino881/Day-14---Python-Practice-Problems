# Day-14 - Python-Practice-Problems

Overview

Day 14 was focused on hands-on Python practice problems to strengthen core programming concepts through real code implementation.

Instead of learning new theory, this day emphasizes problem-solving, logical thinking, and applying previously learned concepts such as variables, conditions, loops, functions, strings, lists, dictionaries, and exception handling.

Practicing problems is essential for:

 Improving logic building
 Writing clean and efficient code
 Preparing for interviews and real-world projects

---

Topics Practiced

 Conditional logic (`if / elif / else`)
 Loops (`for`, `while`)
 Functions and return values
 String operations and validation
 Lists and dictionaries usage
 User input handling
 Exception handling (`try / except`)
 Real-world style mini problems

---

Sample Practice Concepts

```python
# Example: Username validation
username = input("Enter username: ")

if len(username) < 3:
    print("Username too short")
elif not username.isalpha():
    print("Username must contain only letters")
else:
    print(f"Welcome {username}")
```

```python
# Example: Exception handling
try:
    num = int(input("Enter a number: "))
    print(10 / num)
except ZeroDivisionError:
    print("Cannot divide by zero")
except ValueError:
    print("Invalid input")
```

---

Key Takeaways

 Practice improves confidence more than theory alone
 Writing small programs daily builds strong fundamentals
 Errors help understand Python behavior deeply
 Consistency matters more than complexity

---

