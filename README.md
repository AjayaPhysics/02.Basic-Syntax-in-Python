# 02.Basic-Syntax-in-Python
# Basic Syntax in Python

| **Concept**                 | **Description**                                                                                                                                                            | **Example**                          |
|-----------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------|
| **Case Sensitivity**        | Python is case-sensitive, meaning `variable` and `Variable` are treated as two different identifiers.                                                                      | `name = "Alice"` vs `Name = "Bob"`  |
| **Indentation**             | Python uses indentation to define code blocks. Indentation is mandatory and replaces braces used in other languages.                                                       | ```python\nif True:\n    print("Hello")\n```                                |
| **Comments**                | Comments start with a `#` for single-line comments and triple quotes (`'''` or `"""`) for multi-line comments.                                                            | `# This is a comment`               |
| **Variables**               | Variables are used to store data and do not require explicit declaration.                                                                                                  | `x = 10`                            |
| **Keywords**                | Reserved words in Python that cannot be used as variable names, like `if`, `else`, `while`.                                                                                 | `if x > 5:`                         |
| **Print Statement**         | Used to display output to the console.                                                                                                                                    | `print("Hello, World!")`            |
| **Input Statement**         | Used to take user input from the console.                                                                                                                                | `name = input("Enter your name: ")` |
| **Comments Style**          | Single-line comments use `#`. Multi-line comments are surrounded by triple quotes.                                                                                       | ```python\n# Single-line comment\n"""\nMulti-line comment\n"""\n```                            |
| **Dynamic Typing**          | Python is dynamically typed, meaning variable types are determined at runtime.                                                                                             | `x = 5` (int), `x = "Hi"` (str)    |
| **Semicolons**              | Python does not require semicolons to terminate statements, though they can be used optionally.                                                                             | `print("Hello")`                    |
| **Whitespace**              | Excess whitespace between statements is ignored, but indentation within code blocks must be consistent.                                                                     | `y = 5` (valid)                     |
| **Quotation Marks**         | Strings can be defined using single (`'`) or double (`"`) quotes.                                                                                                          | `'Python'` or `"Python"`           |
| **Escape Characters**       | Special characters in strings, such as newlines (`\n`) or tabs (`\t`), are represented using escape sequences.                                                            | `"Hello\nWorld"`                   |
| **Identifiers**             | Names for variables, functions, and objects must start with a letter or underscore, followed by letters, numbers, or underscores.                                           | `my_var = 10`                      |
| **Arithmetic Operators**    | Operators like `+`, `-`, `*`, `/`, `**` (exponentiation), `%` (modulo), and `//` (floor division) are supported.                                                           | `x = 5 + 3`                        |
| **Boolean Values**          | Python supports `True` and `False` as boolean values.                                                                                                                      | `x = True`                         |
| **Built-in Functions**      | Functions like `len()`, `type()`, `str()`, `int()`, and `float()` are readily available.                                                                                   | `print(len("Hello"))`              |



# Basic Syntax in Python

| **Concept**                 | **Description**                                                                                                                                                            | **Example**                          |
|-----------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------|
| **Case Sensitivity**        | Python is case-sensitive, meaning `variable` and `Variable` are treated as two different identifiers.                                                                      | `name = "Alice"` vs `Name = "Bob"` |
| **Indentation**             | Python uses indentation to define code blocks. Indentation is mandatory and replaces braces used in other languages.                                                       | ```python
if True:
    print("Hello")
```                                |
# Python Basic Syntax

| **Concept**              | **Description**                                                                                                                            | **Example**                                                                 |
|--------------------------|--------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------|
| **Case Sensitivity**     | Python is case-sensitive, meaning `variable` and `Variable` are treated as two different identifiers.                                      | `name = "Alice"` vs `Name = "Bob"`                                          |
| **Indentation**          | Python uses indentation to define code blocks. Indentation is mandatory and replaces braces used in other languages.                       | ```python\nif True:\n    print("Hello")\n```                                |
| **Comments**             | Comments start with a `#` for single-line comments and triple quotes (`'''` or `"""`) for multi-line comments.                             | `# This is a comment`                                                       |
| **Variables**            | Variables are used to store data and do not require explicit declaration.                                                                  | `x = 10`                                                                    |
| **Keywords**             | Reserved words in Python that cannot be used as variable names, like `if`, `else`, `while`.                                               | `if x > 5:`                                                                 |
| **Print Statement**      | Used to display output to the console.                                                                                                    | `print("Hello, World!")`                                                    |
| **Input Statement**      | Used to take user input from the console.                                                                                                 | `name = input("Enter your name: ")`                                         |
| **Comment Styles**       | Single-line comments use `#`. Multi-line comments are surrounded by triple quotes.                                                       | ```python\n# Single-line comment\n"""\nMulti-line comment\n"""\n```         |
| **Dynamic Typing**       | Python is dynamically typed, meaning variable types are determined at runtime.                                                            | `x = 5` (int), `x = "Hi"` (str)                                             |
| **Semicolons**           | Python does not require semicolons to terminate statements, though they can be used optionally.                                           | `print("Hello")`                                                            |
| **Whitespace**           | Excess whitespace between statements is ignored, but indentation within code blocks must be consistent.                                   | `y = 5` (valid)                                                             |
| **Quotation Marks**      | Strings can be defined using single (`'`) or double (`"`) quotes.                                                                         | `'Python'` or `"Python"`                                                    |
| **Escape Characters**    | Special characters in strings, such as newlines (`\n`) or tabs (`\t`), are represented using escape sequences.                            | `"Hello\\nWorld"`                                                           |
| **Identifiers**          | Names for variables, functions, and objects must start with a letter or underscore, followed by letters, numbers, or underscores.        | `my_var = 10`                                                               |
| **Arithmetic Operators** | Operators like `+`, `-`, `*`, `/`, `**` (exponentiation), `%` (modulo), and `//` (floor division) are supported.                          | `x = 5 + 3`                                                                 |
| **Boolean Values**       | Python supports `True` and `False` as boolean values.                                                                                    | `x = True`                                                                  |
| **Built-in Functions**   | Functions like `len()`, `type()`, `str()`, `int()`, and `float()` are readily available.                                                  | `print(len("Hello"))`                                                       |
| **Control Structures**   | Python uses `if`, `elif`, and `else` for conditional execution, and loops like `for` and `while` for repeated execution.                  | ```python\nif x > 0:\n    print("Positive")\nelse:\n    print("Non-positive")\n``` |
| **Function Syntax**      | Functions are defined using the `def` keyword, followed by the function name and parameters in parentheses.                               | ```python\ndef greet(name):\n    return f"Hello, {name}!"\n```              |
| **Class Syntax**         | Classes are defined using the `class` keyword, with attributes and methods defined inside.                                               | ```python\nclass Dog:\n    def __init__(self, name):\n        self.name = name\n``` |
| **Importing Modules**    | Use the `import` keyword to include external modules or packages in your code.                                                           | ```python\nimport math\nprint(math.sqrt(4))\n```                            |
| **Error Handling**       | Use `try`, `except`, and `finally` to handle exceptions gracefully.                                                                      | ```python\ntry:\n    x = 10 / 0\nexcept ZeroDivisionError:\n    print("Cannot divide by zero")\n``` |
| **Lambda Functions**     | Anonymous functions can be created using the `lambda` keyword.                                                                           | `square = lambda x: x * x`                                                  |
| **List Comprehensions**  | A concise way to create lists based on existing lists.                                                                                   | `[x * x for x in range(5)]`                                                 |
| **Decorators**           | Functions that modify the behaviour of other functions.                                                                                  | ```python\ndef decorator(func):\n    def wrapper():\n        print("Before")\n        func()\n        print("After")\n    return wrapper\n``` |
| **Logical Operators**    | Operators like `and`, `or`, and `not` are used for combining or negating boolean expressions.                                           | ```python\nx = True and False\nprint(not x)\n```                            |
| **Membership Operators** | `in` and `not in` are used to check membership in sequences like lists, tuples, and strings.                                             | ```python\nif 'a' in 'apple':\n    print("Found")\n```                      |
| **Identity Operators**   | `is` and `is not` are used to compare object identities.                                                                                 | ```python\nx = [1, 2]\ny = x\nprint(x is y)\n```                            |
| **Augmented Assignment** | Combines an operator with assignment, like `+=`, `-=`, `*=`.                                                                             | ```python\nx = 5\nx += 2\nprint(x)\n```                                     |
| **Iterable Unpacking**   | Splits elements of an iterable into multiple variables.                                                                                 | ```python\nx, y = [1, 2]\nprint(x, y)\n```                                  |
| **With Statement**       | Simplifies resource management, like file handling.                                                                                     | ```python\nwith open('file.txt', 'r') as file:\n    content = file.read()\n``` |
| **Generators**           | Functions that yield values lazily using `yield`.                                                                                       | ```python\ndef generator():\n    yield 1\n    yield 2\n```                  |
| **Iterators**            | Objects that implement the `__iter__()` and `__next__()` methods for iteration.                                                          | ```python\nit = iter([1, 2, 3])\nprint(next(it))\n```                       |
