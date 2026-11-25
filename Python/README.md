# Python

Python is a high-level, interpreted, general-purpose programming language known for its simple syntax, readability, and extensive libraries.

## Python Topics

<details>
<summary><b>Python</b></summary>

<details>
<summary><b>1. Python Fundamentals</b></summary>

- [1.1 Introduction](#11-introduction)
- [1.2 Input and Output](#12-input-and-output)
- [1.3 Variables](#13-variables)
- [1.4 Operators](#14-operators)
- [1.5 Keywords](#15-keywords)
- [1.6 Data Types](#16-data-types)
- [1.7 Conditional Statements](#17-conditional-statements)
- [1.8 Loops](#18-loops)
- [1.9 Functions](#19-functions)

</details>

<details>
<summary><b>2. Python Data Structures</b></summary>

- [2.1 String](#21-string)
- [2.2 List](#22-list)
- [2.3 Set](#23-set)
- [2.4 Tuple](#24-tuple)
- [2.5 Dictionary](#25-dictionary)
- [2.6 Array](#26-array)

</details>

<details>
<summary><b>3. Advanced Python</b></summary>

- [3.1 OOPs](#31-oops)
- [3.2 Exception Handling](#32-exception-handling)
- [3.3 File Handling](#33-file-handling)

</details>

</details>

---

# 1. Python Fundamentals

## 1.1 Introduction

### Python is used for:

- Web development – Django, Flask, FastAPI.
- Data analytics – Pandas, NumPy.
- Artificial Intelligence – TensorFlow, PyTorch.
- Machine Learning – Scikit-learn.
- Automation – Shell scripts, file processing.
- Backend development – APIs and server-side applications.

## 1.2 Input and Output

## 1.3 Variables

A variable is a named reference used to store data that can be accessed and manipulated in a program.

**Syntax:**

```python
variable_name = value
```

**Example:**

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

## 1.4 Operators

Operators are symbols or keywords used to perform operations on variables and values.

Python has seven major categories of operators:

1. Arithmetic operators
2. Comparison operators
3. Logical operators
4. Assignment operators
5. Identity operators
6. Membership operators
7. Bitwise operators

---

### 1. Arithmetic Operators

Arithmetic operators perform mathematical calculations.

| Operator | Name | Example | Result |
| :--- | :--- | :--- | :--- |
| `+` | Addition | `10 + 5` | `15` |
| `-` | Subtraction | `10 - 5` | `5` |
| `*` | Multiplication | `10 * 5` | `50` |
| `/` | Division | `10 / 5` | `2.0` |
| `//` | Floor division | `10 // 3` | `3` |
| `%` | Modulus | `10 % 3` | `1` |
| `**` | Exponentiation | `2 ** 3` | `8` |

---

### 2. Comparison Operators

Comparison operators compare two values and return `True` or `False`.

| Operator | Name | Example | Result |
| :--- | :--- | :--- | :--- |
| `==` | Equal to | `10 == 5` | `False` |
| `!=` | Not equal to | `10 != 5` | `True` |
| `>` | Greater than | `10 > 5` | `True` |
| `<` | Less than | `10 < 5` | `False` |
| `>=` | Greater than or equal to | `10 >= 10` | `True` |
| `<=` | Less than or equal to | `10 <= 5` | `False` |

---

### 3. Logical Operators

Logical operators combine conditional statements.

| Operator | Description | Example (`x = 5`) | Result |
| :--- | :--- | :--- | :--- |
| `and` | Returns `True` if both statements are true | `x > 2 and x < 10` | `True` |
| `or` | Returns `True` if one of the statements is true | `x > 2 or x > 10` | `True` |
| `not` | Reverses the result, returns `False` if the result is true | `not(x > 2 and x ` | |

### 4. Assignment Operators

### 5. Identity Operators

### 6. Membership Operators

### 7. Bitwise Operators

## 1.5 Keywords

## 1.6 Data Types

A data type defines the type of value that a variable can hold.

Python is dynamically typed, meaning you do not need to explicitly declare a variable's type.

### A. Numeric Data Types

Python has three main numeric types.

#### 1. Integer (int)

Stores whole numbers without decimal points.

**Example**

```python
age = 22
marks = 85

print(age)
print(marks)
print(type(age))
```

#### 2. Float (float)

Stores decimal numbers.

**Example**

```python
salary = 25000.50
percentage = 85.75

print(salary)
print(percentage)
print(type(salary))
```

#### 3. Complex (complex)

Stores numbers containing real and imaginary parts.

**Example**

```python
x = 2 + 3j

print(x)
print(x.real)
print(x.imag)
```

### B. String (str)

A string is a sequence of characters enclosed in single, double, or triple quotes.

**Example**

```python
name = "Sandesh"
city = 'Pune'
message = """Welcome to Python"""

print(name)
print(city)
print(message)
```

### C. Boolean (bool)

Boolean represents only two values:

- True
- False

Python uses capital T and F in Boolean values.

**Example**

```python
is_developer = True
is_student = False

print(is_developer)
print(is_student)

print(type(is_developer))
```

## 1.7 Conditional Statements

Conditional statements are used to make decisions in a Python program based on whether a condition is True or False.

Python provides the following conditional statements:

1. if
2. if-else
3. if-elif-else
4. Nested if
5. Short-hand if
6. Ternary operator

### 1. The if Statement

The if statement executes a block of code only when a specified condition is true.

**Example**

```python
age = 22

if age >= 18:
    print("Eligible to vote")
```

**Output:**

```text
Eligible to vote
```

### 2. The if-else Statement

The if-else statement executes one block when the condition is true and another block when it is false.

**Example**

```python
number = int(input("Enter a number: "))

if number % 2 == 0:
    print("Even number")
else:
    print("Odd number")
```

**Output:**

```text
Enter a number: 15
Odd number
```

### 3. The if-elif-else Statement

When you have multiple conditions to check, use if-elif-else.

elif means "else if".

Python checks the conditions from top to bottom. The first true condition gets executed, and the remaining conditions are skipped.

**Example**

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

**Output**

```text
Enter your marks: 82
Grade B
```

### 4. Nested if Statements

A nested if statement means writing an if statement inside another if statement.

It is useful when one condition needs to be checked only after another condition is satisfied.

**Example**

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

**Output:**

```text
Enter username: sandesh
Enter password: python123
Login successful
```

### 5. Short-hand if Statement

Python allows you to write a simple if statement in one line.

**Example**

```python
age = 22

if age >= 18: print("Adult")
```

**Output:**

```text
Adult
```

### 6. Ternary Operator (Conditional Expression)

A ternary operator allows you to write an if-else condition in a single line.

**Example**

```python
number = 10

result = "Even" if number % 2 == 0 else "Odd"

print(result)
```

**Output**

```text
Even
```

## 1.8 Loops

Loops are used to execute a block of code repeatedly until a particular condition is satisfied or a sequence is completed.

### 1. For Loop

A for loop is used to iterate over a sequence such as a list, tuple, string, dictionary, or range of numbers.

**Example**

```python
#print numbers from  1 to 5
for i in range(1, 6):
    print(i)
```

**Output**

```text
1
2
3
4
5
```

### 2. While Loop

A while loop repeatedly executes a block of code as long as its condition remains true.

**Example**

```python
i=1
while i<=5
    print(i)
i+=1
```

**Output**

```text
1
2
3
4
5
```

## 1.9 Functions

---

# 2. Python Data Structures

## 2.1 String

## 2.2 List

## 2.3 Set

## 2.4 Tuple

## 2.5 Dictionary

## 2.6 Array

---

# 3. Advanced Python

## 3.1 OOPs

## 3.2 Exception Handling

## 3.3 File Handling
