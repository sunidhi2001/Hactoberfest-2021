# Hactoberfest-2021
# Python program to reverse a string

def reverse(s):
str = ""
for i in s:
	str = i + str
return str

s = "hacktoberfest"

print ("The original string is : ",end="")
print (s)

print ("The reversed string is : ",end="")
print (reverse(s))
