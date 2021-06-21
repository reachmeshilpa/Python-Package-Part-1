# Python-Package-Part-1
Learning by implementation

import keyword
'''
  to print
 
'''
# the number of keywords in the current version of Python
print (len (keyword.kwlist))

# to print the list of keywords in the current version of Python
print ( keyword.kwlist)

'''
to print 
'''
# the above two commands in a single coding line
print ( len (keyword.kwlist), keyword.kwlist)

# A continuation character or backslash is used for a multiline python statement
number = 1 + 2 +\
         3 + 4 + \
         5
print (number)
# or we can just use brackets for a multiline python statement
number2 = (1 + 2 +
           3 + 4 + 5 + 6)
print (number2)

# Rules to create a variable name
'''
   It can only begin with an underscore or an alphabet
   It can include underscore, alphabet (lower or upper -case) and a number
   It cannot include special symbols except and underscore
   It cannot begin with a number
 '''
 # Mutlitple variables can be assigned in a single line by separating with a comma
 var_1, _var2 = 2, 3
 print (var_1, _var2)
 
 # When two variables are assigned the same value, they are stored by the same ID number
 var3 = var4 = 4
 print (var3, var4)
 
 # To check the location id of a variable, use id()
 id ( var3, var4 )
 # Python saves space by storing the same value for different variables in one location
 
 
 
 
 
 
