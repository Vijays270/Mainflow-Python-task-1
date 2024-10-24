# Mainflow-Python-task-1

1. ##List -> (create, add, remove, modify)
# Creating a List
fruit_list = ["Apple", "Banana", "Orange", "Cherry"]

# Adding Element in List
fruit_list.append("Pineapple")

# Removing Element from List
fruit_list.remove("Banana")

# Modifying Element in List
fruit_list[1] = "Mango"

print("Updated List:", fruit_list)

Updated List: ['Apple', 'Mango', 'Cherry', 'Pineapple']



2.Dictionary -> (create, add, remove, modify)

# Creating a Dictionary
car_dict = {"Brand": "BMW", "Model": "Suv", "Year": 2020}

# Adding Element in Dictionary
car_dict["Loc"] = "Germany"

# Removing Element from Dictionary
del car_dict["Year"]

# Modifying Element in Dictionary
car_dict["Brand"] = "BMW Motors"

print("Updated Dictionary:", car_dict)
Updated Dictionary: {'Brand': 'BMW Motors', 'Model': 'Suv', 'Loc': 'Germany'}


3.Set -> (create, add, remove, modify)
# Creating a Set
color_set = {"White", "Black", "Yellow", "Purple"}

# Adding Element in Set
color_set.add("Red")

# Removing Element from Set
color_set.remove("Yellow")

# Modifying Element in Set
color_set.discard("White")
color_set.add("Maroon")

print ("Updated Set:", color_set)
Updated Set: {'Red', 'Purple', 'Black', 'Maroon'}

