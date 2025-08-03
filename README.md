# Week2-Assignment
# Creating an empty list
my_list = []
print("Step 1 - Empty list:", my_list)
Output: []

# Appending the numbers 10, 20, 30, 40
my_list.append(10)
print("Append 10:", my_list)
Output: [10]

my_list.append(20)
print("Append 20:", my_list)
Output: [10, 20]

my_list.append(30)
print("Append 30:", my_list)
Output: [10, 20, 30]

my_list.append(40)
print("Append 40:", my_list)
Output: [10, 20, 30, 40]

# Inserting number 15 at the second position 
my_list.insert(1, 15)
print("Step 3 - Insert 15 at index 1:", my_list)
Output: [10, 15, 20, 30, 40]

# Extending my_list with [50, 60, 70]
my_list.extend([50, 60, 70])
print("Step 4 - Extend with [50, 60, 70]:", my_list)
Output: [10, 15, 20, 30, 40, 50, 60, 70]

# Removing the last element from the extended my_list
my_list.pop()
print("Step 5 - Remove last element:", my_list)
Output: [10, 15, 20, 30, 40, 50, 60]

# Sorting the my_list in ascending order
my_list.sort()
print("Step 6 - Sorted list:", my_list)
Output: [10, 15, 20, 30, 40, 50, 60]

# Finding and printing the index of 30
index_of_30 = my_list.index(30)
print("Step 7 - Index of 30:", index_of_30)
Output: 3
