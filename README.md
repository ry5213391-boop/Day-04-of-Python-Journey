# Day-04-of-Python-Journey
# =====================================
# Day 04 - Python Lists
# Author: Roshan Yadav
# =====================================

print("===== DAY 04 : PYTHON LISTS =====\n")

# 1. What is a List?
print("1. LIST BASICS")

fruits = ["Apple", "Banana", "Mango"]
print("Original List:", fruits)

# -------------------------------------

# 2. List Operations Using Functions
print("\n2. LIST OPERATIONS")

fruits.append("Orange")
print("After append():", fruits)

fruits.insert(1, "Grapes")
print("After insert():", fruits)

fruits.remove("Banana")
print("After remove():", fruits)

fruits.pop()
print("After pop():", fruits)

print("Length of list:", len(fruits))

fruits.sort()
print("After sort():", fruits)

fruits.reverse()
print("After reverse():", fruits)

print("Count of Apple:", fruits.count("Apple"))
print("Index of Mango:", fruits.index("Mango"))

# -------------------------------------

# 3. Number List Operations
print("\n3. NUMBER LIST OPERATIONS")

numbers = [10, 5, 20, 15, 25]

print("Numbers:", numbers)
print("Maximum:", max(numbers))
print("Minimum:", min(numbers))
print("Sum:", sum(numbers))

numbers.sort()
print("Sorted Numbers:", numbers)

# -------------------------------------

# 4. Nested Lists
print("\n4. NESTED LISTS")

matrix = [
    [1, 2, 3],
    [4, 5, 6],
    [7, 8, 9]
]

print("Nested List:")
print(matrix)

print("Element at Row 2 Column 3:", matrix[1][2])

# -------------------------------------

print("\n===== DAY 04 COMPLETED SUCCESSFULLY =====")
