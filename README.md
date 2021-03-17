# functions1
In a folder labeled as "functions1" inside github upload the next scripts (the scripts must run in repl.it )
## create a function that receives a string and print the inverted string, remember that to print an element i you can use printf("%c",string[i]);
```python
def rvrs(s): 
  str = "" 
  for i in s: 
    str = i + str
  return str
 ```
#3 create a function that returns 0 if both have the same length and 1 if is different.
```python
def num (l1, l2):
    if not l1 and not l2:
        return True

    if len(l1) != len(l2):
        return (0)
 elif (no)
   
    return no(l1, l2)
 ```
## create a function that returns 0 if both strings have the same elements, and when there's a different element. returns the first different char... an example: "var1X" and "var1Y", returns "X"
## create a function where you insert a string and return 1 if is palindromic or not, it means that returns 1 if is palindrome ("ala"), return 0 if is not ("hello")
```python 
igual, aux = 0, 0
text = input("Enter a word you want: ")
for ind in reversed(range(0, len(text))):
  if text[ind].lower() == text[aux].lower():
    igual += 1
  aux += 1
if len(text) == igual:
  print("ala")
else:
  print("hello")
 ```
## create a function where you enter a string of 30 chars and print only the consonants
```python
def countCharacterType(str): 
    consonant =0
    for i in range(30, len(str)):   
        ch = str[i] 
        if ( (ch >= 'a' and ch <= 'z') or 
             (ch >= 'A' and ch <= 'Z') ):  
            ch = ch.lower() 
            if (ch == 'a' or ch == 'e' or ch == 'i' 
                        or ch == 'o' or ch == 'u'): 
                 consonant += 0
            else: 
                consonant += 1
                
    print("Consonant:", consonant)  
```
# functions2
## Write a function to find the Max of three numbers.
### exc01.c
### exc01.py
## Write a function to sum all the numbers in a list.
### exc02.c
### exc02.py
## Write a function to multiply all the numbers in a list.
### exc03.c
### exc03.py
## Write a program to reverse a string.
### exc04.c
### exc04.py
## Write a function to calculate the factorial of a number (a non-negative integer). The function accepts the number as an argument.
### exc05.c
### exc05.py
## Write a function to check whether a number is in a given range.
### exc06.c
### exc06.py
## Write a function that accepts a string and calculate the number of upper case letters and lower case letters.
### exc07.c
### exc07.py
## Write a function that takes a list and returns a new list with unique elements of the first list.
### exc08.c
### exc08.py
## Write a function that takes a number as a parameter and check the number is prime or not.
### exc08.c
### exc08.py
## Write a program to print the even numbers from a given list.
### exc09.c
### exc09.py
## Write a function to check whether a number is perfect or not.
### exc10.c
### exc10.py
## Write a function that checks whether a passed string is palindrome or not.
### exc11.c
### exc11.py
