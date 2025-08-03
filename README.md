# Week2-Assignment
# Creating an empty list
my_list = []

# Appending the numbers; 10, 20, 30, 40
my_list.append(10)
my_list.append(20)
my_list.append(30)
my_list.append(40)

# Inserting 15 at the second position in the list
my_list.insert(1, 15)

# Step 4: Extending my_list with a another list of [50, 60, 70]
my_list.extend([50, 60, 70])

# Step 5: Remove the last element
my_list.pop()

# Step 6: Sort in ascending order
my_list.sort()

# Step 7: Find and print the index of 30
index_of_30 = my_list.index(30)

# Output results
print("Final list:", my_list)
print("Index of 30:", index_of_30)
Final list: [10, 15, 20, 30, 40, 50, 60]
Index of 30: 3


Edit
Final list: [10, 15, 20, 30, 40, 50, 60]
Index of 30:
