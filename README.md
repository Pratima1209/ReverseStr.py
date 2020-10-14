# ReverseStr.py

# Reverse string

def reverse(string):                          #Function 
    reversed_str=""                           #Empty string for reversed string storage
    for i in string:
        reversed_str=i+reversed_str           #Concatinate
    return reversed_str

string=input("Enter the String :")
print "Original String is :",string
print "Reversed=",reverse(string)             # Function call
