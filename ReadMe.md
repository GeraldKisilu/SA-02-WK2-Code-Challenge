# (SA 02 WK2 Code Challenge)

#### Date, 2024/03/31

#### By *Gerald Muli*

## Description
It's a website that presents the breakdown of the week 2 code challenge into the required solutions as per the required task

## Installation
You use git clone to be able to download the documents in the GitHub

## Installation Requirements
Git

### Installation instruction
```
Git clone 

```

# Live Link
[Git]()

## Technologies used
Github
Javascript
ReadMe

## Support and contact details


### License
The content of this site is licensed under the MIT license
Copyright (c) 2024.




# NO.1> Explained
Created a function called swapCase that takes a string (str) as input.
Initialized an empty string called result to store the swapped case characters.
Iterated through each character in the input string using a for loop.
Checked if the character is uppercase by comparing it with its uppercase version.
If the character is uppercase, converting it to lowercase and then appending it to the result string.
If the character is lowercase, converting it to uppercase and  then appending it to the result string.
Returned the final result string with swapped case characters.



# NO.2> Explained
Defined a function generateArray that takes two numbers num1 and num2 as input.
Created an empty array result to store the generated array.
Used a for loop to iterate from num1 to num2.
In each iteration, I pushed the current number into the result array.
Once the loop was complete, I returned the result array containing the generated array

# NO.3> Explained
The isPrime function takes a number as input and checks if it is a prime number.
It first checks if the number is less than or equal to 1, in which case it returns false.
Then, it iterates from 2 to the square root of the number to check if the number is divisible by any other number.
If the number is divisible by any other number, it returns false, indicating that it is not a prime number.
Otherwise, it returns true, indicating that the number is a prime number.
The findPrimeNumbers function takes an array of numbers as input and filters out only the prime numbers using the isPrime function.
It returns a new array containing only the prime numbers from the original array, preserving their order.