# built-in-function
# Program to demonstrate List and its Built-in Functions

# creating a list
numbers = [10, 20, 30, 40, 50]
print("Original List:", numbers)

# append() - add an element at the end
numbers.append(60)
print("After append(60):", numbers)

# insert() - add element at specific index
numbers.insert(1, 15)
print("After insert(1, 15):", numbers)

# remove() - remove a specific element
numbers.remove(30)
print("After remove(30):", numbers)

# pop() - removes element from given index
numbers.pop(2)
print("After pop(2):", numbers)

# extend() - add another list to current list
numbers.extend([70, 80])
print("After extend([70, 80]):", numbers)

# count() - count occurrences of an element
print("Count of 20:", numbers.count(20))

# index() - returns index of an element
print("Index of 50:", numbers.index(50))

# sort() - sort in ascending order
numbers.sort()
print("After sort():", numbers)

# reverse() - reverse the list
numbers.reverse()
print("After reverse():", numbers)

# copy() - create duplicate list
copy_list = numbers.copy()
print("Copied List:", copy_list)

# len() - length of list
print("Length of list:", len(numbers))

# max(), min(), sum() - mathematical operations
print("Maximum value:", max(numbers))
print("Minimum value:", min(numbers))
print("Sum of list:", sum(numbers))

# clear() - remove all items from the list
numbers.clear()
print("After clear():", numbers)
