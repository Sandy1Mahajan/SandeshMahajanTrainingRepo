# Python

Python is a high-level, interpreted, general-purpose programming language known for its simple syntax, readability, and extensive libraries.

## Python Topics

<details>
<summary><b>Python</b></summary>

<details>
<summary><b>1. Python Introduction</b></summary>

- [What is Python?](#what-is-python)
- [Applications of Python](#applications-of-python)

</details>

<details>
<summary><b>2. Variables</b></summary>

- [What are Variables?](#what-are-variables)
- [Variable Syntax](#variable-syntax)
- [Variable Examples](#variable-examples)

</details>

<details>
<summary><b>3. Data Types</b></summary>

- [What are Data Types?](#what-are-data-types)
- [Numeric Data Types](#numeric-data-types)
  - [Integer (int)](#integer-int)
  - [Float](#float)
  - [Complex](#complex)
- [String (str)](#string-str)
- [Boolean (bool)](#boolean-bool)

</details>

<details>
<summary><b>4. Type Conversion</b></summary>

- [What is Type Conversion?](#what-is-type-conversion)
- [Implicit Type Conversion](#implicit-type-conversion)
- [Explicit Type Conversion](#explicit-type-conversion)

</details>

<details>
<summary><b>5. Input in Python</b></summary>

- [input() Function](#input-function)
- [Taking Integer Input](#taking-integer-input)
- [Taking Float Input](#taking-float-input)
- [Taking Multiple Inputs](#taking-multiple-inputs)
- [Student Information System](#student-information-system)

</details>

<details>
<summary><b>6. Operators in Python</b></summary>

- [Arithmetic Operators](#arithmetic-operators)
- [Comparison Operators](#comparison-operators)
- [Logical Operators](#logical-operators)
- [Assignment Operators](#assignment-operators)
- [Identity Operators](#identity-operators)
- [Membership Operators](#membership-operators)
- [Bitwise Operators](#bitwise-operators)
- [Operator Precedence](#operator-precedence)
- [Employee Salary Calculator](#employee-salary-calculator)
- [Interview Questions](#operator-interview-questions)
- [Practice Exercises](#operator-practice-exercises)

</details>

<details>
<summary><b>7. Conditional Statements</b></summary>

- [What are Conditional Statements?](#what-are-conditional-statements)
- [if Statement](#if-statement)
- [if-else Statement](#if-else-statement)
- [if-elif-else Statement](#if-elif-else-statement)
- [Nested if](#nested-if)
- [Short-hand if](#short-hand-if)
- [Ternary Operator](#ternary-operator)

</details>

<details>
<summary><b>8. Loops in Python</b></summary>

- [What are Loops?](#what-are-loops)
- [for Loop](#for-loop)
- [while Loop](#while-loop)
- [break Statement](#break-statement)
- [continue Statement](#continue-statement)
- [pass Statement](#pass-statement)

</details>

</details>

---

# Python Notes

## What is Python?

Python is a high-level, interpreted, general-purpose programming language known for its simple syntax, readability, and extensive libraries.

## Applications of Python

- Web development – Django, Flask, FastAPI.
- Data analytics – Pandas, NumPy.
- Artificial Intelligence – TensorFlow, PyTorch.
- Machine Learning – Scikit-learn.
- Automation – Shell scripts, file processing.
- Backend development – APIs and server-side applications.

---

## What are Variables?

A variable is a named reference used to store data that can be accessed and manipulated in a program.

## Variable Syntax

```python
variable_name = value
```

## Variable Examples

```python
name = "Sandesh"
age = 22
city = "Pune"
salary = 20000.00
is_developer = True

print(name)
print(age)
print(city)
print(salary)
print(is_developer)
```

**Output:**

```text
Sandesh
22
Pune
20000.0
True
```

---

## What are Data Types?

A data type defines the type of value a variable can hold. Python is dynamically typed, so we do not need to declare a variable's data type explicitly.

## Numeric Data Types

### Integer (int)

Integer stores whole numbers without decimal points.

```python
age = 22
marks = 85

print(age)
print(marks)
print(type(age))
```

### Float

Float stores numbers containing decimal points.

```python
salary = 25000.50
percentage = 85.75

print(salary)
print(percentage)
print(type(salary))
```

### Complex

Complex numbers contain a real part and an imaginary part.

```python
x = 2 + 3j

print(x)
print(x.real)
print(x.imag)
```

## String (str)

A string is a sequence of characters enclosed in single, double, or triple quotation marks.

```python
name = "Sandesh"
city = 'Pune'
message = """Welcome to Python"""

print(name)
print(city)
print(message)
```

## Boolean (bool)

Boolean represents one of two values: `True` or `False`. Python uses a capital T and F.

```python
is_developer = True
is_student = False

print(is_developer)
print(is_student)

print(type(is_developer))
```

---

## What is Type Conversion?

Type conversion means converting a value from one data type to another.

### Implicit Type Conversion

Python automatically converts one data type into another when required.

### Explicit Type Conversion

The programmer manually converts a value using functions such as `int()`, `float()`, and `str()`.

---

## Input in Python

The `input()` function is used to accept data from the user.

### input() Function

### Taking Integer Input

### Taking Float Input

### Taking Multiple Inputs

### Student Information System

---

## Operators in Python

Operators are symbols or keywords used to perform operations on variables and values.

There are seven main categories of operators:

1. Arithmetic Operators
2. Comparison Operators
3. Logical Operators
4. Assignment Operators
5. Identity Operators
6. Membership Operators
7. Bitwise Operators

## Arithmetic Operators

| Operator | Name | Example | Result |
|---|---|---|---|
| + | Addition | 10 + 5 | 15 |
| - | Subtraction | 10 - 5 | 5 |
| * | Multiplication | 10 * 5 | 50 |
| / | Division | 10 / 5 | 2.0 |
| // | Floor division | 10 // 3 | 3 |
| % | Modulus | 10 % 3 | 1 |
| ** | Exponentiation | 2 ** 3 | 8 |

## Comparison Operators

| Operator | Name | Example | Result |
|---|---|---|---|
| == | Equal to | 10 == 5 | False |
| != | Not equal to | 10 != 5 | True |
| > | Greater than | 10 > 5 | True |
| < | Less than | 10 < 5 | False |
| >= | Greater than or equal to | 10 >= 10 | True |
| <= | Less than or equal to | 10 <= 5 | False |

## Logical Operators

| Operator | Description | Example |
|---|---|---|
| and | Returns True if both conditions are true | `x > 2 and x < 10` |
| or | Returns True if at least one condition is true | `x > 2 or x > 10` |
| not | Reverses the result | `not(x > 2)` |

## Assignment Operators

## Identity Operators

## Membership Operators

## Bitwise Operators

## Operator Precedence

## Employee Salary Calculator

## Operator Interview Questions

## Operator Practice Exercises

---

## What are Conditional Statements?

Conditional statements are used to make decisions in a program based on whether a condition is `True` or `False`.

Types of conditional statements:

1. if
2. if-else
3. if-elif-else
4. Nested if
5. Short-hand if
6. Ternary operator

## if Statement

```python
age = 22

if age >= 18:
    print("Eligible to vote")
```

**Output:**

```text
Eligible to vote
```

## if-else Statement

```python
number = int(input("Enter a number: "))

if number % 2 == 0:
    print("Even number")
else:
    print("Odd number")
```

**Output (input: 15):**

```text
Odd number
```

## if-elif-else Statement

```python
marks = int(input("Enter your marks: "))

if marks >= 90:
    print("Grade A")
elif marks >= 75:
    print("Grade B")
elif marks >= 60:
    print("Grade C")
elif marks >= 40:
    print("Grade D")
else:
    print("Fail")
```

**Output (input: 82):**

```text
Grade B
```

## Nested if

```python
username = input("Enter username: ")
password = input("Enter password: ")

if username == "sandesh":
    if password == "python123":
        print("Login successful")
    else:
        print("Incorrect password")
else:
    print("Invalid username")
```

**Output (username: sandesh, password: python123):**

```text
Login successful
```

## Short-hand if

```python
age = 22

if age >= 18: print("Adult")
```

**Output:**

```text
Adult
```

## Ternary Operator

```python
number = 10

result = "Even" if number % 2 == 0 else "Odd"

print(result)
```

**Output:**

```text
Even
```

---

## What are Loops?

Loops are used to execute a block of code repeatedly until a condition is satisfied or a sequence is completed.

## for Loop

```python
# Print numbers from 1 to 5
for i in range(1, 6):
    print(i)
```

**Output:**

```text
1
2
3
4
5
```

## while Loop

```python
i = 1

while i <= 5:
    print(i)
    i += 1
```

**Output:**

```text
1
2
3
4
5
```

## break Statement

## continue Statement

## pass Statement
