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

