# pythonexercises. Exercise 1. 

# Create a program that asks the user to enter their name and their age. Print out a message addressed to them that tells them the year that they will turn 100 years old.

# Extras:

# 1)Add on to the previous program by asking the user for another number and printing out that many copies of the previous message. (Hint: order of operations exists in Python)
# 2)Print out that many copies of the previous message on separate lines. (Hint: the string "\n is the same as pressing the ENTER button)

# Personal Solution.
users_name = input('Cual es su nombre? ')
birth_day = input('Cual es su edad? ')
many_times_msg = input('Cuantas veces desea ver el mensaje? ')

hundred_years = (2019 - int(birth_day)) + 100

print(f'\n Hola {users_name} usted tendra 100 años en {hundred_years}.' * int(many_times_msg))
