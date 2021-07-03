# Python-Package-Part-1
Learning by implementation

PYTHON--VERSION

command + enter: run on mac

import keyword
'''
  to print
 
'''
# quotes mark the beginning and the end of a string

# String is the text that I want to print, it is encasee within quotes and can be number or alphabets
print('Hello world!')
print ("print('what to print')")

# a. Printing in three lines
print('Hello world!')
print('Hello world!')
print('Hello world!')
#when all three are run together
OUTPUT->
Hello world!
Hello world!
Hello world!

# b. Printing in three lines smartly
print('Hello world!\nHello world!\nHello world!')
OUTPUT->
Hello world!
Hello world!
Hello world!

# Concatanetation of two strings using arithematic operation or STRING CONCATENATION
a. print('Hello' + 'Shilpa')
OUTPUT-> HelloShilpa
b. print('Hello' + ' Shilpa')
OUTPUT->Hello Shilpa
c.print('Hello' + ' ' + 'Shilpa') #works everytime, most reliable
OUTPUT->Hello Shilpa




# single or double quote is the same for python but this data is stored always in double quote


#**Syntax/Quotatio Error** if I type print ('Hello World!) ending quotation **mark is absent**

# Unexpected EOF while parsing
print((“New lines can be created with a backslash and n.”)
#Two open parenthesis and one closed so computer thinks you are going to continue the code block
to correct
print(“New lines can be created with a backslash and n.”)

#**Indentation/Leading White Space Error**
> print()
instead of >print()
# print('Hello'+' '+
         'Shilpa')

# the number of keywords in the current version of Python
print (len (keyword.kwlist))

# to print the list of keywords in the current version of Python
print ( keyword.kwlist)

'''
to print 
'''
# the above two commands in a single coding line
print ( len (keyword.kwlist), keyword.kwlist)

# PRINT OUTPUT
print ('the output will be displayed on screen')
OUTPUT -> the output will be displayed on screen

integer = 4

# using (,variable) -> extra space is what we get
print ('the value of integer is ',integer)
OUTPUT -> the value of integer is  4

# using ()+str -> extra space is removed
print ('the value of integer is ')+str(integer)
OUTPUT -> the value of integer is 4

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
   Only alphabet can come after an underscore
 '''
 # Mutlitple variables can be assigned in a single line by separating with a comma ?????NW
 var_1, _var2 = 2, 3
 print (var_1, _var2)
 
 # Variables can be created and print command can be given in the same line ?????NW
 print (var_5 = 4, var_6 = 5)
 
 
 # When two variables are assigned the same value, they are stored by the same ID number
 var3 = var4 = 4
 print (var3, var4)
 
 # To check the location id of a variable, use id()
 id ( var3, var4 )
 
 # Python saves space by storing the same value for different variables in one location
 
 # Quote rules
 '' mkdcmkmcl' kmkmlml ''       Single quote can be within a duoble quote pair
 ' bjknjknlkml " njnklmlkm'     Double quote can be within a single quote pair
 Double within double and single within single DOESNOT WORK
 
 message = 'Shilpa's coding quest' will not work as the in between single quote would mean an end of the string
 To deal with such an issue there are two ways:
 message = ''Shilpa's coding quest'' or 'Shilpa''s coding quest'
 print (message)
 or use\ before the in between quote
 message = 'Shilpa\'s coding quest'
 print (message)
 or put in triple quote and multiple lines
 message = '''Shilpa's coding questhas a good beginning
 fron June 2021.'''
 
 # num = 1
 num = num + 1
 print (num)
 OUTPUT-> 2
 
 shortcut
 num = 1
 num += 1
 print (num)
 OUTPUT ->2

# to print the absolute value, which is always positive
print (abs(-3))
OUTPUT-> 3

# to round off a number
print (round(3.7578656454, 4))
OUTPUT-> 3.7579

# To convert a numerical looking string to an integer use int()
num_1 = '100'
num_2 = '200'
print (num_1 + num_2)
OUTPUT-> 100200 #it gets concatenated as the values are of class string

num_1 = int(num_1)
num_2 = int(num_2)
print (num_1 + num_2)
OUTPUT-> 300

# to round off to a certain decimal
print (round(3.75, 1))
OUTPUT-> 3.8

 # Some functions with a string
  
 message = 'codingG Questt' # to count the **full length** print(len(variable)) of the value of the variable
 print (len (message))
 OUTPUT-> 13

message = 'codinG Questt'
 print (message.count (codinG))      # to **count** the length of a **part** of value-> print(variable.count ())
 OUTPUT-> 6

message = 'codinG Questt'
 print (message.count (codinG))      # to **count** the number of **same alphabet** in the value-> print(variable.count ('t'))
 OUTPUT-> 2


 message = 'codinG Questt'
 print (message.lower())
 OUTPUT-> coding questt
 
 message = 'codinG Questt'
 print (message))
 OUTPUT-> CODING QUESTT
 
 # to find a value of a string
message = 'codinG Questt'
 print (message.find('codinG'))
 OUTPUT-> 1                        #output 1 when the word/numeric is found in our variable's value
 
 message = 'codinG Questt'
 print (message.find('Shilpa'))
 OUTPUT-> -1                       #output negative 1 when the word/numeric is NOT found in our variable's value
 
 # to replace one value with another
 message = 'codinG Questt'
 message.replace('Questt', 'enthusiast')
 OUTPUT-> will not work, one has to form and print a new variable (working)
 new_message = message.replace('quest', 'enthusiast')
 print (new_message)
 OUTPUT-> codinG enthusiast
 
 # How to print the output in a specific format say Hola, Shilpa. Beinvenido!
 1.
 greeting = 'Hola'
 name = 'Shilpa'
 message = greeting + ', ' + name + '.Bienvenido!' #string method
 print (message)
 OUTPUT->

2. 
 greeting = 'Hola'
 name = 'Shilpa'
 message = '{}, {}.Welcome!' #string and curly braces method
 message = 
 print (message)
 OUTPUT->

3.
greeting = 'Hola'
 name = 'Shilpa'
 message = greeting + ', ' + name + '.Bienvenido!'.format(greeting, name)
 print (message)
 OUTPUT->

4. 
 greeting = 'Hola'
 name = 'Shilpa'
 message = f'{greeting}, {name}. Welcome!'      f'{},{}'.  #f, string and curly braces method
 print (message)
 OUTPUT-> Hola, Shilpa. Beinvenido!
 
print (dir(message))
OUTPUT-> '__add__', '__class__', '__contains__', '__delattr__', '__dir__', '__doc__', '__eq__', '__format__', '__ge__', '__getattribute__', '__getitem__', '__getnewargs__', '__gt__', '__hash__', '__init__', '__init_subclass__', '__iter__', '__le__', '__len__', '__lt__', '__mod__', '__mul__', '__ne__', '__new__', '__reduce__', '__reduce_ex__', '__repr__', '__rmod__', '__rmul__', '__setattr__', '__sizeof__', '__str__', '__subclasshook__', 'capitalize', 'casefold', 'center', 'count', 'encode', 'endswith', 'expandtabs', 'find', 'format', 'format_map', 'index', 'isalnum', 'isalpha', 'isascii', 'isdecimal', 'isdigit', 'isidentifier', 'islower', 'isnumeric', 'isprintable', 'isspace', 'istitle', 'isupper', 'join', 'ljust', 'lower', 'lstrip', 'maketrans', 'partition', 'removeprefix', 'removesuffix', 'replace', 'rfind', 'rindex', 'rjust', 'rpartition', 'rsplit', 'rstrip', 'split', 'splitlines', 'startswith', 'strip', 'swapcase', 'title', 'translate', 'upper', 'zfill']


 
 
 
 
