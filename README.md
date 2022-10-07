# Exception-Handling

## Quickfire Five

Out of line code - subroutine/not the main program

In line code - main program/any line of code

import random as rd allows random to be replaced by rd. rd.randint(0,10)

import randint() from random specifically takes randomint from the module. No longer need to do random.randint only randint.

Key difference betweeen UTF-32 and UTF-16/UTF-8 - 32 is fixed length 4 bytes, others are variable length.

String manipulation functions:

- string.upper()
- string[:4]
- string.lower()
- capitalize()
- isdigit()
- str1 + str2

## **Exception Handling**

for i in range(2):
  
  t = input("Enter a number or...a string by mistake ")
  
  try:
    
    result = int(t) * int(t)
    
    print(result)
  
  except:
    
    print("Oops - something unexpected happened")

print("Program finished")

Try and Except is used for when you cannot predict the error. It keeps the program running even if there is an issue rather than outputting an error message. It might offer an alternative or a message e.g Oops - something unexpected happened. It is useful so the uesr does not receive an error message that they do not understand.

F-strings are a way of formatting print statements in Python (nothing to do with exceptions)
Allows you to not have to open and close strings within a print. Instead you can add variables using {}. 

(Finally statement)

