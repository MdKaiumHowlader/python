#1 Find the sum of all elements in a list
number = [10, 11, 12, 13, 14]
sum_of_this_number = sum(number)
print("sum of the number:",sum_of_this_number)

#2 Find the largest and smallest number in a list

number = [10, 20, 30, 40, 50]
largest = max(number)
smallest = min(number)
print("largest number:", largest)
print("smallest number:", smallest)

#3 Remove duplicate elements from a list

number = [2, 3, 3, 4, 4, 5, 6, 7, 6]
unique_number = list(set(number))
print("list_with_out_duplicate:", unique_number)

#4. Reverse a list without using built-in functions

#6. Convert a list into a tuple

my_list = [2, 3, 4, 5]
my_tuple = tuple(my_list)
print("Covert list to tuple:", my_tuple)

##7. Find the index of an element in a tuple

my_tuple = (10, 20, 30, 40, 50)
index = my_tuple.index(30)
print("index of 30:", index)

# 8. Count how many times an element appears in a tuple

my_tuple = (1, 2, 1, 3, 1, 4, 1)
count = my_tuple.count(1)
print("count how many time 2 have in my tuple:", count)

# 9. Check if an element exists in a tuple

my_tuple = (1, 2, 3, 4, 5, 6, 7, 9)
element = 15
if element in my_tuple:
    print(f"{element} exists in the tuple")
else:
    print(f"{element} does not exist in the tuple")

✅ 10. Concatenate two tuples

tuple1 = (1, 2, 3)
tuple2 = (4, 5, 6)
result = tuple1 + tuple2 
print("Concatenated tuple:", result)
