# assignment-2-2-

#ASSIGNMENT 2:

#Write a Python program to print a dictionary whose keys should be the alphabet
#from a-z and the value should be corresponding ASCII values

my_dict = {}  #create a dictionary
 
for i in range(97, 97 + 26):   
    my_dict[chr(i)] = i
 
print(my_dict)
