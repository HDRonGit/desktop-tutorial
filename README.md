# Welcome to GitHub Desktop!

This is your README. READMEs are where you can communicate what your project is and how to use it.

Write your name on line 6, save it, and then head back to GitHub Desktop.
HDRonGit
# Classify a single number.
# import time

print("We ask you to enter 5 numbers to see if the number is negative or positive.")

number = int(input("Enter a number the first number: ")) # Askes the user to enter the first number.

if number > 0:
    count_pos = number + 1
        
elif number < 0:
    count_neg = number + 1
    
else:
    count_zero = number + 1

    
number = int(input("Enter a number the second number: ")) # Askes the user to enter the second number.

if number > 0:
    count_pos = number + 1
        
elif number < 0:
    count_neg = number + 1
    
else:
    count_zero = number + 1
    
number = int(input("Enter a number the thirth number: ")) # Askes the user to enter the thirth number.

if number > 0:
    count_pos = number + 1
        
elif number < 0:
    count_neg = number + 1
    
else:
    count_zero = number + 1
    
number = int(input("Enter a number the forth number: ")) # Askes the user to enter the forth number.

if number > 0:
    count_pos = number + 1
        
elif number < 0:
    count_neg = number + 1
    
else:
    count_zero = number + 1
    
number = int(input("Enter a number the forth number: ")) # Askes the user to enter the forth number.

if number > 0:
    count_pos = number + 1
        
elif number < 0:
    count_neg = number + 1
    
else:
    count_zero = number + 1
    # time.sleep(200)
print(count_pos, "numbers are Positive")
print(count_neg, "numbers are Negative")
print(count_zero, "numbers are Zero")

