# Python Operators

**Sub parts**

- [Arithmetic Operators](#arithmetic-operators)
- [Concatenate Strings](#concatenate-strings)
- [Program to Compute Amount After Discount](#program-to-compute-discount)
- [**Task**: Kilometers to Miles](#programming-task)

---

An operator is a symbol that is used to perform operations om values and variables.

The most frequently used operator is `=`. It is used to assign data to a variable.

```python
name = "Anand Khandekar"
print(name)   # Anand Khandekar
```

---

## Arithmetic Operators

Here's a list of arithmetic operators:

```
Addition: +
Subtraction: -
Multiplication: *
Division: /
Floor division: //
Remainder: %
Exponent: **

```

## Examples: Arithmetic Operators

```python
# Arithmetic operators in action

x = 5

result = x + 10 # addition
print(result)   # 15

result = x - 10 # subtraction
print(result)   # -5

result = x * 10 # multiplication
print(result)    # 50

result = x / 10 # division
print(result)   # 0.5

result = x ** 2   # exponent
print(result)     # 25

quotient = x // 2  # floor division
remainder = x % 2  # modulus

print("Quotient is", quotient) # 2
print("Remainder is", remainder) # 1

```

---

## Using parentheses

We can use parentheses to make code more readable.

```python
# harder to understand

number = 34 * 5 - 5 / 3 # 168.33333
print(number)

# easier to understand

number = (34 * 5) - (5 / 3) # 168.33333
print(number)

```

---

## Concatenate Strings

If the `+` operator is used with strings, it concatenates the strings.

```python
str1 = "Hey "
str2 = "Jude"
print(str1 + str2) # Hey Jude

```

---

## More on Assignment Operators

**Multiple assignment at once**

```python
x, y = 5, 6  # one to one correspondence
print(x) # 5
print(y) # 6

```

**Compound Assignment Operators**

```python
x = 5
x += 10 # x = x + 10
x -= 10 # x = x - 10

```

---

## Program to Compute Discount

**Assume a suitable value for distance 2 cities(in km). Write a program to convert and print this distance in meters, feet, inches and centimeter**


```python
# Program to convert Kilometers to meters
km = int(input("Enter the value in kilometers: "))

# 1 Kilometre = 1000 meters
mul_factor = 1000

# Converting km to m.
m = km * mul_factor

print("The entered value in meter: ", m)

```

---

## Programming Task

**Can you create a program to convert distance in kilometers to miles?**

**Formula: 1 kilometer -> 0.621371 miles**

```python
# Program to convert kilometers to files

distance_km = 564.5

conversion_ratio = 0.621371

distance_miles = distance_km * conversion_ratio

print(distance_miles) # 350.7639295

```
