# print() Function and Variables

**Video Link:** 

- [Program to Print Strings](#print-function)
- [Program to Print Numbers](#program-to-print-numbers)
- [Store Data in a Variable](#program-to-print-numbers)
- [Assign one Variable to Another](#assign-one-variable-to-another)
- [Print Multiple Objects in One print()](#print-multiple-objects-in-one-print)

***

## print() Function

The `print()` is a built-in function in Python. It prints whatever object that is inside the parentheses `()`.

### Program to Print Strings

A string is a textual data. They must be wrapped inside quotation marks( either single or double).

```python
# Printing Strings

print('Hello World')
print("Python 3.9.2 is the latest is the latest released version")
```

**Output**

```
Hello World
Python 3.9.2 is the latest is the latest released version
```

---

### Program to Print Numbers

The `print()` function can also be used to print numbers. There are two commonly used numeric data in Python:

- integers: 5, -34, 0 etc.
- floating-point numbers: 5.0, -45.2, 3.5 etc.

```python
# Printing numbers

print(42)
print(3.14)
```

**Output**

```
42
3.14
```

---

## Variables in Python

We use variables to store data and use them later in the program.

### Store Data in a Variable

We use the `=` operator to assign a value to a variable.

```python
# store data in variables and print them

countryity = "India"
print(country)
```

**Output**

```
India
```

---

### Change Value Stored in a Variable

We can also change the data a variable holds.

```python
# change value of a variable

city = "Mumbai"
print(city)

city = "Pune"
print(city)
```

**Output**

```
Mumbai
Pune
```

---

### Assign one Variable to Another

```python
# assign one variable to another

x = 22.7
y=100

x = y
print(x)
```

**Output**

```
100
```

---

## Print Multiple Objects in One print()

We can print multiple objects in a single `print()` function by separating them with commas.

```python
# print two objects in one print()

city = "Kathmandu"
print("City:", city)
```

**Output**

```
City: Kathmandu
```

When we print more than one object in a single `print()` function, they are by default separated by commas.

```python
# print four objects in one print()

city = "Kathmandu"
kfc_locations = 3
print("City:", city, "KFC Locations:", kfc_locations)
```

**Output**

```
City: Kathmandu KFC Locations: 3
```

---

## Giving Good Variable Names

We should always try to give descriptive and meaningful variable names so that it's easier to understand our code.
