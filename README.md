# python100
#random_name_choice
import random

names_string=input("Give me everybody's names, separated by a comma: ")


names = names_string.split(", ")

#find the length of string

l_names=len(names)

random_index=random.randint(0,(l_names-1))
random_name=names[random_index]
print(f"{random_name} is going to buy the meal today!")
