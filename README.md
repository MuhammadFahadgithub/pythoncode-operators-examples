# pythoncode-operators-examples

1. Arithmetic Operators (arithmetic_operators.py)

# Arithmetic Operators in Python
a = 10
b = 3

print("Addition:", a + b)
print("Subtraction:", a - b)
print("Multiplication:", a * b)
print("Division:", a / b)
print("Floor Division:", a // b)
print("Modulus:", a % b)
print("Exponentiation:", a ** b)

2. Assignment Operators (assignment_operators.py)

# Assignment Operators in Python
x = 5
x += 3  # Equivalent to x = x + 3
print("x after += 3:", x)

x -= 2
print("x after -= 2:", x)

x *= 4
print("x after *= 4:", x)

x /= 2
print("x after /= 2:", x)

x //= 2
print("x after //= 2:", x)

x %= 3
print("x after %= 3:", x)

x **= 2
print("x after **= 2:", x)

3. Comparison Operators (comparison_operators.py)

# Comparison Operators in Python
a = 10
b = 5

print("a == b:", a == b)
print("a != b:", a != b)
print("a > b:", a > b)
print("a < b:", a < b)
print("a >= b:", a >= b)
print("a <= b:", a <= b)

4. Logical Operators (logical_operators.py)

# Logical Operators in Python
x = True
y = False

print("x and y:", x and y)  # False
print("x or y:", x or y)    # True
print("not x:", not x)      # False

5. Identity Operators (identity_operators.py)

# Identity Operators in Python
a = [1, 2, 3]
b = [1, 2, 3]
c = a

print("a is b:", a is b)  # False (different objects in memory)
print("a is c:", a is c)  # True (same object)
print("a is not b:", a is not b)  # True

6. Membership Operators (membership_operators.py)

# Membership Operators in Python
nums = [1, 2, 3, 4, 5]

print("3 in nums:", 3 in nums)  # True
print("6 in nums:", 6 in nums)  # False
print("10 not in nums:", 10 not in nums)  # True

7. Bitwise Operators (bitwise_operators.py)

# Bitwise Operators in Python
a = 5  # 0101 in binary
b = 3  # 0011 in binary

print("a & b:", a & b)  # 0001 (1)
print("a | b:", a | b)  # 0111 (7)
print("a ^ b:", a ^ b)  # 0110 (6)
print("~a:", ~a)        # -6 (inverts bits)
print("a << 1:", a << 1)  # 1010 (10) (Left shift)
print("a >> 1:", a >> 1)  # 0010 (2) (Right shift)

