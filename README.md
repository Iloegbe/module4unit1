# Project 1

name = input("enter your name")
age = int(input("enter your age"))
def age_in_100(age):
    year_to_be_100 = 2019 - int(age) + 100
    return year_to_be_100
    
calculated_year = age_in_100(age)
    
print("Hello", name, "you are", age,  "you will be 100 in", calculated_year "!")
    







num = int(input("Enter a num"))
if (num % 2) == 0:
    print("This is an even number")
else:
    print("This is an odd number")
