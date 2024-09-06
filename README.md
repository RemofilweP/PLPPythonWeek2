# Create an empty list called my_list
my_list = []

print("Original Empty List: ", my_list)

# Append the following elements to my_list: 10, 20, 30, 40
my_list.append(10)
my_list.append(20)
my_list.append(30)
my_list.append(40)

print("Populated List: ", my_list)

# Insert the value 15 at the second position in the list
my_list[1] = 15

print("List with update to position 2: ", my_list)

# Extend my_list with another list: [50, 60, 70]
new_list = [50, 60, 70]

my_list.extend(new_list)

print("Extended List: ", my_list)

# Remove the last element from my_list
del my_list[-1]

print("List with last element removed: ", my_list)

#Sort my_list in ascending order
sorted_list = sorted(my_list)

print("Sorted List: ", sorted_list)

#Find and print the index of the value 30 in my_list
value_30_index = my_list.index(30)

print("The number 30 is found at index: ", value_30_index)

