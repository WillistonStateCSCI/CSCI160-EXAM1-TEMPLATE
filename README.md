# CSCI160-EXAM1
Programming portion of Exam 1 for CSCI 160  
## Q1 Instructions - Upper and Lower Cases  
Write a program that asks the user to enter a word.  
The program should then print the word in uppercase, in lowercase and then print the original word.  
*Note: if multiple words are entered, the program should only accept and print the first word as in Tests 4 and 5.*  
### Q1 Test 1  
**Input:**  
smile  
**Output:**  
The word in uppercase letters is SMILE  
The word in lowercase letters is smile  
The original word is smile  
### Q1 Test 2  
**Input:**  
SHOUT  
**Output:**  
The word in uppercase letters is SHOUT  
The word in lowercase letters is shout  
The original word is SHOUT  
### Q1 Test 3  
**Input:**  
WoBbLe    
**Output:**  
The word in uppercase letters is WOBBLE  
The word in lowercase letters is wobble  
The original word is WoBbLe  
### Q1 Test 4  
**Input:**  
SO many WoRdS!    
**Output:**  
The word in uppercase letters is SO  
The word in lowercase letters is so  
The original word is SO  
### Q1 Test 5  
**Input:**  
256 is a number that should not crash my program   
**Output:**  
The word in uppercase letters is 256  
The word in lowercase letters is 256  
The original word is 256  
## Q2 Instructions - Email Verifier  
Write a program that asks the user to input an Email address.
If the text entered does not contain an @ symbol and a period, it is not an Email address and should inform the user.  
*Note: to get Test 5 to pass, you must find a way to check if the @ symbol appears before . in the email address.*  
### Q2 Test 1  
**Input:**  
bob   
**Output:**  
This is not an email address   
### Q2 Test 2  
**Input:**  
bob@smiledotcom   
**Output:**  
This is not an email address   
### Q2 Test 3  
**Input:**  
bobatsmile.com   
**Output:**  
This is not an email address  
### Q2 Test 4  
**Input:**  
bob@smile.com   
**Output:**  
This is an email address  
### Q2 Test 5  
**Input:**  
com.smile@bob    
**Output:**  
This is not an email address  
## Q3 Instructions - Minimum Number  
Write a program that asks the user to enter how many numbers they want to check.  
Then, the user will be able to enter that many integers.
Once all integers are entered, the program will tell the user which number is smallest. 

A sample run of the code may look like this:
```
How many numbers would you like to compare?  
5
Enter integer 1 > 5
Enter integer 2 > 2
Enter integer 3 > 1
Enter integer 4 > 4
Enter integer 5 > 3
The minimum is 1
```

*Note: if the user enters 0 or a negative number in response to the first question, the program should prompt them again as in Tests 4 and 5*  
*The code shown below is an example of a successful run that would pass Test 4.*
```                                                             
How many numbers would you like to compare?                                                                                                                                                               
0
Sorry, please enter a number greater than 0.  How many numbers would you like to compare?  
0
Sorry, please enter a number greater than 0.  How many numbers would you like to compare?  
0
Sorry, please enter a number greater than 0.  How many numbers would you like to compare?  
5
Enter integer 1 > 0
Enter integer 2 > -1
Enter integer 3 > -5
Enter integer 4 > -3
Enter integer 5 > -2
The minimum is -5
```
### Q3 Test 1  
**Input:**  
1  
5   
**Output:**  
The minimum is 5  
### Q3 Test 2  
**Input:**  
5  
5  
4  
3  
2  
1    
**Output:**  
The minimum is 1  
### Q3 Test 3  
**Input:**  
3  
-5  
12  
5        
**Output:**  
The minimum is -5  
### Q3 Test 4  
**Input:**  
0  
0  
0  
5  
0  
-1  
-5  
-3  
-2         
**Output:**  
The minimum is -5  
### Q3 Test 5  
**Input:**  
-999  
2  
7  
5           
**Output:**  
The minimum is 5  
## Q4 Instructions - Sum of Integers
Write a program that asks the user to enter two integers, then gives the sum of all the numbers including and between the two numbers entered.  
For example, if the user enters 2 and 4, the sum would be 2+3+4 or 11.

If the user enters both numbers the same, the sum should just be the number that was entered.

*Note:  Your program should still work even if the user enters the larger number first.  How can you ensure your code works either way?*

### Q4 Test 1  
**Input:**  
1  
10            
**Output:**  
The sum of the integers from 1 to 10 is 55
### Q4 Test 2  
**Input:**  
-10  
-5            
**Output:**  
The sum of the integers from -10 to -5 is -45  
### Q4 Test 3  
**Input:**  
0  
100              
**Output:**  
The sum of the integers from 0 to 100 is 5050  
### Q4 Test 4  
**Input:**  
100  
0              
**Output:**  
The sum of the integers from 0 to 100 is 5050  
### Q4 Test 5  
**Input:**  
200  
-200              
**Output:**  
The sum of the integers from -200 to 200 is 0  