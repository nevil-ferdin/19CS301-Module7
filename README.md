# 19CS301-Module7

- **Name:** Nevil Joe Ferdin P
- **Register Number:** 212222050041
## EX: 7.1 RECURSION
### Aim:
To Write a Python Program to find the sum of all digits in a number using recursion
### Algorithm:
**Step 1 :** Start.

**Step 2 :** Define a function.

**Step 3 :** Create a base case for termination of the function. 
**Step 4 :** Create a recursive case to calculate the result.

**Step 5 :** Print the result. **Step 6 :** Stop.

### Program:
```python
def sum_digit(n):
       if n<=0:
            return 0
       else:
            return n%10+sum_digit(n//10)
n = int(input())
sum = sum_digit(n)
print(sum)
```
### Output:
![image](https://github.com/user-attachments/assets/50acc657-266e-46e6-ab17-10358494e26c)

### Result: 
Thus, the given program is implemented and executed successfully .

## EX: 7.2 TYPES OF RECURSIONS
### Aim:
To Write a Python Program to find the sum of all digits in a number using recursion
### Algorithm:
**Step 1 :** Start.

**Step 2 :** Define a function.

**Step 3 :** Create a recursive case in the first line of function for head recursion.

**Step 4 :** Print the result.

**Step 5 :** Stop.
### Program:
```python
def fun(n):
     if (n >0):
          fun(n - 2)
      print(n-1, end=" ")
x = int(input())
if(x%2==0):
     fun(x)
else:
     fun(x+1)

```
### Output:
![image](https://github.com/user-attachments/assets/c4d6416f-d333-49c1-9dd5-0f774cdabb03)

### Result: 
Thus, the given program is implemented and executed successfully.
 
## EX: 7.3 TAYLOR SERIES

### Aim:
To python program to evaluate the series using recursion by collecting the x and n values from the user.
### ALGORITHM:
**Step 1 :** Start.

**Step 2 :** Create a variable x and n.

**Step 3 :** Get the values of x and n from user.

**Step 4 :** Create a base case and recursive case to calculate the result.

**Step 5 :** Print the result.

**Step 6 :** Stop.
### Program:
```python
def series(x,n):
         if n==0:
            return 1
         else:
            return x**n/n+series(x,n-1)
x = int(input())
n = int(input())
print(series(x,n))
```
### Output:
![image](https://github.com/user-attachments/assets/1d00b1a4-cecb-466f-8593-805f00d27461)

 
### Result: 
Thus, the given program is implemented and executed successfully .


 

## EX: 7.4 Solve by recursion relation

### Aim: 
To Write a Python Program to find whether a string is a palindrome or not using recursion

### Algorithm:
**Step 1 :** Start.

**Step 2 :** Define a function.

**Step 3 :** Create a base case and recursive case to calculate the result.

**Step 4 :** Create a variable and get input from user.

**Step 5 :** : Call the function.

**Step 6 :** Print the result.

STEP 7: Stop.

### Program:
```python
def is_palindrome(word):
      if len(word)<1:
            return True
      else:
            if word[0]==word[-1]:
                 return is_palindrome(word[1:-1])
             else:
                  return False
word = str(input())
if is_palindrome(word)==True:
        print("String is a palindrome")
else:
        print("String is not a palindrome")
```
### Output:
![image](https://github.com/user-attachments/assets/d30ef836-1901-448a-a146-dc905fdc3198)

### Result: 
Thus, the given program is implemented and executed successfully .
 
