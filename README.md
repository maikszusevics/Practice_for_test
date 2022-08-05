# Practice for test

# Lists, Tuples, Dictionaries, Indexing
```
# List syntax is []
example_list = ["this", "is", "a", "list", 1, 2, 3, True, ["list inside", "another list"], 3.14, 6.99]
# the list above shows that it is possible to have different data types in one list

# Indexing - index starts at 0 - syntax just [] or [:] to specify
print(example_list[0:1]) # outputs a list with only "this"
print(example_list[:6]) # outputs 1 - 6th item in list as a list
print(example_list[4:8]) # outputs 4th to 8th item in list as a list
print(example_list[2]) # outputs the 3rd item in list

# lists are MUTABLE:
example_list.append("adding to a list") #this adds to the list
#print(example_list)
example_list.remove(2) # this removes from the list
# print(example_list)
example_list.pop(0) # this removes from the list based on index
# print(example_list)

# Tuples
# tuples are stored in parentheses ()
# Tuples are for data that doesnt get changed because it is IMMUTABLE
# tuples can have MULTIPLE DATA TYPES
example_tuple = ("planet", "solar system", "galaxy", "supercluster")
# print(example_tuple)
# print(example_tuple[0]) # same indexing rules apply
# print(example_tuple[2:4])


# DICTIONARIES contain Key : Value pairs
# dictionary syntax is {key : value}
example_dic = {"milk" : "too expensive",
               "bread" : "more than it used to be",
               "wheat for bread" : "being burnt by the Russians",
               "eggs" : "reasonable price... If you buy factory caged not free range :(",
               "ham?" : "more like SCAM",}

print(example_dic.keys())
```
