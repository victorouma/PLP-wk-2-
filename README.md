# PLP-wk-2-
my_list = list()
my_list = []  # Create an empty list

my_list.append(10)
my_list.append(20)
my_list.append(30)
my_list.append(40)

print(my_list)  # Output: [10, 20, 30, 40]
my_list.insert(1, 15)  # Insert 15 at index 1
my_list.extend([50, 60, 70])
# Now: [10, 15, 20, 30, 40, 50, 60, 70]
my_list.pop()  # Removes 70
# Now: [10, 15, 20, 30, 40, 50, 60]
my_list.sort()
# Now: [10, 15, 20, 30, 40, 50, 60] (unchanged since already sorted)
index_of_30 = my_list.index(30)
print("Index of 30:", index_of_30)  # Output: 3
print("Final list:", my_list)  # Output: [10, 15, 20, 30, 40, 50, 60]
print("Index of 30:", index_of_30)  # Output: 3
