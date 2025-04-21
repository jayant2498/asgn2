# asgn2
Asgn2

number = int(input('Enter a number:' )) #number (variable) takes integer input from the user
if number%2==0:                         # checks if number mod 2 == 0 ie the number is divisible by 2 leaving no remainder
    print(number,'is an even number')   # if yes then it's an even number
else:
    print(number,'is an odd number')    # else it's an odd number



sum = 0                                 # creating a variable sum and initialising it the value 0 so as to iterate over i and store the value in sum
for i in range(1,51):                   # iterating with i variable using the range function 1 -> start and it goes until 50 exclusing 51
    sum = sum+i                         # storing the value of sum in the variable sum after evaluating the expression
    i+=1                                # iterating the value until 50 
print('the sum of numbers from 1 to 50 is:',sum) # finally displaying the result , outside the loop so as to get a single line answer 
