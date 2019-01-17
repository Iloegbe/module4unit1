# module4unit1
#this program tells the user to input thier name and age
#it uses the information provided to calculate thier age in 100 years
name = input("enter your name")
age = int(input("enter your age"))
def age_in_100(age):
    year_to_be_100 = 2019 - int(age) + 100
    return year_to_be_100
    
calculated_year = age_in_100(age)
    
print("Hello", name, "you are", age,  "you will be 100 in", calculated_year "!")
    
