# Experiment-7
Experiment 7 : Study of while loop in python
### Naman Bothra
### 25070123078

### Aim : 
Study of while loops in python

### Theory : 
A while loop in Python is a looping statement that repeats a block of code as long as a given condition is True.

# How it works

Python checks the condition.

If the condition is True, the loop body runs.

After execution, the condition is checked again.

The loop continues until the condition becomes False.

# Important Points

The condition must eventually become False.

Otherwise, it creates an infinite loop.

Indentation is mandatory in Python.

### Algorithm :

1. Algorithm: Print Numbers from 1 to n Using While Loop

Start

Prompt the user to enter a number.

Read the input and store it in the variable n.

Initialize a variable i and set it equal to 1.

Check whether i is less than or equal to n.

If the condition is true:

Display the value of i.

Increment i by 1.

Repeat Step 5.

If the condition becomes false, exit the loop.

Stop

2. Algorithm: Find Factorial of a Number Using While Loop

Start

Prompt the user to enter a number.

Read the input and store it in the variable n.

Initialize a variable fact and set it equal to 1.

Check the value of n:

If n is less than 0, display "Factorial does not exist for negative numbers" and stop.

Else if n is equal to 0, display "The factorial is 1" and stop.

Else (if n is greater than 0), proceed to Step 6.

While n is greater than 0:

Multiply fact by n.

Decrease n by 1.

After the loop ends, display the value of fact as the factorial.

Stop

3(a). Algorithm: Print Fibonacci Series Using While Loop

Start

Prompt the user to enter a number n (number of terms).

Read the input and store it in variable n.

Initialize:

a = 0 (first term)

b = 1 (second term)

i = 1 (counter)

While i is less than or equal to n, repeat:

Display the value of a.

Calculate c = a + b.

Assign a = b.

Assign b = c.

Increment i by 1.

When the condition becomes false, exit the loop.

Stop

3(b). Algorithm: Print Fibonacci Series up to a Given Limit

Start

Prompt the user to enter a number (limit).

Read the input and store it in the variable limit.

Initialize:

a = 0 (first Fibonacci number)

b = 1 (second Fibonacci number)

While a is less than or equal to limit, repeat:

Display the value of a.

Update the values:

Set a = b

Set b = a + b (previous values)

When a becomes greater than limit, exit the loop.

Stop

4. Algorithm: Reverse a Number Using While Loop

Start

Prompt the user to enter a number.

Read the input and store it in the variable n.

Initialize a variable rev and set it to 0.

While n is greater than 0, repeat:

Find the last digit of the number using digit = n % 10.

Update the reversed number as rev = rev × 10 + digit.

Remove the last digit from n using integer division n = n // 10.

When n becomes 0, exit the loop.

Display the reversed number (rev).

Stop

5(a). Algorithm: Check Whether a Number is a Palindrome

Start

Prompt the user to enter a number.

Read the input and store it in the variable num.

Store the original value of num in another variable temp.

Initialize a variable rev and set it to 0.

While num is greater than 0, repeat:

Find the last digit using num % 10.

Update rev = (rev × 10) + last digit.

Remove the last digit from num using integer division (num = num // 10).

After the loop ends, compare temp with rev.

If they are equal, display "Palindrome".

Otherwise, display "Not Palindrome".

Stop

5(b). Algorithm: Check Whether a String is a Palindrome

Start

Assign a string value to variable s.

Initialize two variables:

i = 0 (starting index)

j = length of string − 1 (ending index)

Set a Boolean variable is_palindrome to True.

While i is less than j, repeat:

Compare the characters at positions i and j.

If they are not equal:

Set is_palindrome to False.

Exit the loop.

Otherwise:

Increment i by 1.

Decrement j by 1.

After the loop ends:

If is_palindrome is True, display "Yes".

Otherwise, display "No".

Stop

5(c). Algorithm: Check Whether a String is a Palindrome (Using Reverse Method)

Start

Prompt the user to enter a string.

Read the input and store it in the variable st.

Create a reversed version of the string and store it in the variable rev.

Compare the original string st with the reversed string rev.

If both are equal, display "Palindrome".

Otherwise, display "Not Palindrome".

Stop

6. Algorithm: Count the Number of Digits in a Number

Start

Prompt the user to enter a number.

Read the input and store it in the variable num.

Initialize a variable count and set it to 0.

While num is greater than 0, repeat:

Increment count by 1.

Remove the last digit of num using integer division (num = num // 10).

When num becomes 0, exit the loop.

Display the value of count as the total number of digits.

Stop

7. Algorithm: Search an Element in a List Using While Loop

Start

Create a list nums containing elements (e.g., 10, 20, 30, 40, 50).

Prompt the user to enter the element to search.

Read the input and store it in the variable key.

Initialize a variable i = 0 (index counter).

While i is less than the length of the list, repeat:

Check if nums[i] is equal to key.

If equal:

Display "Element found at index i".

Exit the loop.

Otherwise, increment i by 1.

If the loop completes without finding the element, display "Element not found".

Stop

8. Algorithm: Print Only Odd Numbers from 1 to 10 Using While Loop

Start

Initialize a variable i and set it to 0.

While i is less than 10, repeat:

Increment i by 1.

Check if i is divisible by 2.

If yes (i.e., i % 2 == 0), skip the remaining steps of the loop and continue to the next iteration.

Otherwise, display the value of i.

When the condition becomes false, exit the loop.

Stop

### Conclusion :
Hence  we learnt how to use while loop in python and implemented it in solving various problems and successfully got the result
