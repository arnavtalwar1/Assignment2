#Task1(Explanation)
Input: The line a=int(input("Enter the Number: ")) prompts the user to enter a number and stores it as an integer in the variable a.
Modulo Operator: The core of the logic is a%2. The modulo operator (%) calculates the remainder of a division. In this case, it checks the remainder when a is divided by 2.
Even Numbers: If a number is even, it is perfectly divisible by 2, leaving a remainder of 0. So, a%2 == 0 would be true.
Odd Numbers: If a number is odd, it is not perfectly divisible by 2, leaving a remainder of 1. Therefore, a%2 != 0 would be true.
Conditional Statement: An if-else statement is used to control the program's flow based on the result of the modulo operation.
If a%2 == 0 (the number is even), the program prints "Number is even".
If the condition is false (the number is odd), the program prints "Number is odd". 
The code takes an integer input from the user and then uses the modulo operator and an if-else statement to determine whether the number is even or odd, printing the corresponding message. 

#Task2 (Explanation)
The code adds numbers from 1 to 50. 
sum = 0: This sets a starting point by initializing a variable called "sum" to 0. 
for i in range(1, 51):: This creates a loop that goes through numbers from 1 to 50.
range(1, 51): This generates a sequence of numbers from 1 up to, but not including, 51 (so it stops at 50).
i: In each loop, i takes on a new value from the sequence (1, 2, 3, and so on up to 50).
sum += i: This adds the current value of i to the "sum" variable in each loop.
In the first loop, sum (which is 0) becomes 0 + 1 = 1.
In the second loop, sum (which is 1) becomes 1 + 2 = 3.
This continues until all numbers from 1 to 50 have been added to sum. 
print("The sum of 51 numbers is ", sum): This displays the final value of "sum." 
The code calculates the sum by:
Starting with a total of 0.
Iterating through numbers from 1 to 50.
Adding each number to the total.
Displaying the final total. 
The code will output "The sum of 51 numbers is 1275". This is because the sum of the numbers from 1 to 50 equals 1275. 
