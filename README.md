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
## create a function that returns 0 if both have the same length and 1 if is different.
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
```c
#include <stdio.h>
#include <stdlib.h>
biggestNumber(int,int,int);
int main()
{
    int a,b,c;
    printf("Enter three numbers");
    scanf("%d%d%d",&a,&b,&c);

 
int biggestNumber(int a,int b,int c){
if(a>b)
{
    if(a>c)
    return a;
    else
        return c;
}
else
{
    if(b>c)
        return b;
    else
        return c;
}
}
```
### exc01.py
```python
def max_of_two( a, b ):
    if a > b:
        return a
        return b
def max_of_three( a, b, c ):
    return max_of_two( a, max_of_two( b, c ) )
    
print(max_of_three(1, 2, 3))
```
## Write a function to sum all the numbers in a list.
### exc02.c
```c
#include <stdio.h>
#include <stdlib.h>
 
int sum(int arr[], int n)
{
    int sum = 0; 
 
   
    for (int i = 0; i < n; i++)
    sum += arr[i];
 
    return sum;
}
```
### exc02.py
```python
def sum(numbers):
    total = 0
    for x in numbers:
        total += x
    return total
print(sum((numbers)))
```
## Write a function to multiply all the numbers in a list.
### exc03.c
```c
#include <stdio.h>

int main()
{
    int i, num;
    do
    {
        printf( "\n  Enter whole number: ", 163 );
        scanf( "%d", &numero )

        for ( i = 1 ; i <= 10 ; i++ )
            printf( "\n   %d * %d = %d", i, num, i * num );
    return 0;
}
```
### exc03.py
```python
def multiply(numbers):  
    total = 1
    for x in numbers:
        total *= x  
    return total  
print(multiply((1, 2, 3, 4, 5, 6)))
```
## Write a program to reverse a string.
### exc04.c
```c
#include <iostream>
#include <cstring>

using namespace std;

void inv (char cad[], int wide)
{
    int wide2=wide;
    char inv[wide2];

    for (int x=0, y=wide; x<wide && y>=0; x++, y--)
    {
        inv[x]=cadena[y];
    }
    cout<<"> "<<cadena<<endl;
    cout<<endl<<"> "<<inv<<endl<<endl;
    return;
}

int main ()
{

    char opcion;
    string word;
    int long, long2;

    while (opcion!='n')
    {
        system ("cls");
        cout<<"> Ejercicio"<<endl<<endl;
        cout<<"> Ingrese palabra: ";
        cin>>palabra;
        longitud=palabra.length();

        char cadena[palabra.size()+1];
        strcpy(cadena, palabra.c_str());

        longitud2=strlen(cadena);

        invertidor (cadena,long2);

    return 0;
}
```
### exc04.py
```python
def string_reverse(str1):

    rstr1 = ''
    index = len(str1)
    while index > 0:
        rstr1 += str1[ index - 1 ]
        index = index - 1
    return rstr1
print(string_reverse('1234abcd'))
```
## Write a function to calculate the factorial of a number (a non-negative integer). The function accepts the number as an argument.
### exc05.c
```c
#include <stdio.h> 
 
long int factorial(int n);
int main(void){
 int n;
 printf("Enter numb: ");
 scanf("%d", &n);
 printf("The factorial of %d = %ld", n,factorial(n));
 return 0;
}
long int factorial(int n) {
    if (n>=1)
        return n * factorial(n-1);
    else
        return 1;
}
```
### exc05.py
```python
def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n-1)
n=int(input("Input a num to compute the factiorial : "))
print(factorial(n))
```
## Write a function to check whether a number is in a given range.
### exc06.c
```c
#include <stdio.h>

float range(float n1);
float n;
int main(void){
  float n;
  printf("Enter num: ");
  scanf("%f", &n);
  range(n);
  return 0;
}
float range(float n){
  if(n >=0 && n <= 20) 
	{
		printf("Range [0, 20]");
  }
	else{
	printf("Outside the range\n");
	}	
	return 0;
  }
```
### exc06.py
```python
def test_range(n):
    if n in range(1,11):
        print( " %s is in the range"(n))
    else :
        print("The number is outside the range.")
 return(0)
```
## Write a function that accepts a string and calculate the number of upper case letters and lower case letters.
### exc07.c
```c
```
### exc07.py
```python
def string_test(s):
    d={"upper":0, "lower":0}
    for l in s:
        if l.isupper():
           d["upper"]+=1
        elif c.islower():
           d["lower"]+=1
        else:
           pass
    print ("Original String is  : ", s)
    print ("No. of Upper characters : ", d["upper"])
    print ("No. of Lower Characters : ", d["lower"])
 ```
## Write a function that takes a list and returns a new list with unique elements of the first list.
### exc08.c
```c
```
### exc08.py
```python
def unique_list(l):
  x = []
  for a in l:
    if a not in x:
      x.append(a)
  return x
print(unique_list([1,2,3,3,3,3,4,5])) 
```
## Write a function that takes a number as a parameter and check the number is prime or not.
### exc09.c
```c
#include<stdio.h>  
int main(){    
int n,i,m=0,flag=0;    
	printf("Enter a num to check prime:");    
	scanf("%d",&n);    
	m=n/2;    
		for(i=2;i<=m;i++)    
	{    
		if(n%i==0)    
{    
	printf("Num is not prime");    
	flag=1;    
	break;    
	}    
}    
	if(flag==0)    
	printf("Num is prime");     
	return 0;  
 }    
```
### exc09.py
```python
def prime-test(n):
    if (n==1):
        return False
    elif (n==2):
        return True;
             for s in range(2,n):
            if(n % s==0):
                return False
        return True            
print(prime-test(3))
```
## Write a program to print the even numbers from a given list.
### exc10.c
```c
#include <stdio.h>
    void main()
    {
 
    int array[100], i, num;
        printf("Enter size of array \n");
 
        scanf("%d", &num);
        printf("Enter elements of array \n");
 
        for (i = 0; i < num; i++) 
        {
            scanf("%d", &array[i]);
        }
 
        printf("Even numb in array are - ");
        for (i = 0; i < num; i++) 
        {
            if (array[i] % 2 == 0) 
            {
                printf("%d \t", array[i]);
            }
        }
 
        printf("\n Odd nums in array are -");
        for (i = 0; i < num; i++) 
        {
            if (array[i] % 2 != 0) 
            {
                printf("%d \t", array[i]);
            }
        }
 
    }
```
### exc10.py
```python
def is_even_num(l):
    enum = []
    for n in l:
        if n % 2 == 0:
            enum.append(n)
    return enum
print(is_even_num([1, 2, 3, 4, 5, 6, 7, 8, 9]))
```
## Write a function to check whether a number is perfect or not.
### exc11.c
```c
# include <stdio.h>   

int main()   
{   
 int i, Num, Sum = 0 ;   
  
 printf("\n Enter any num \n") ;
 scanf("%d", &Num) ;   
 
 for(i = 1 ; i < Num ; i++)   
  {   
   if(Num % i = 0)   
     Sum = Sum + i ;   
  }    

 if (Sum = Number)   
    printf("\n %d is a Perfect Num", Num) ;   
 else   
    printf("\n%d is not the Perfect Num", Num) ;   

return 0 ;   
}
```
### exc11.py
```python
def perfect_num(n):
    sum = 0
    for x in range(1, n):
        if n % x == 0:
            sum += x
    return sum == n
print(perfect_num(6))
```
## Write a function that checks whether a passed string is palindrome or not.
### exc12.c
```c
int i;
  int len=strlen(string);
  for(i=len-1; i>=0; i--){
    if(string[len-i-1]!=string[i]){
      return 0;
    }
  }
  return 1;
}

int function1(char string[MAX])
{
  int length1 = strlen()
}

int main(void) {
  char mystring1[MAX] = "This is a string";
  char mystring2[MAX] = "a string";
  printf("the value for string 1 is %lu and len10 result is %d \n",strlen(mystring1),len10(mystring1));
  printf("the value for string 2 is %lu and len10 result is %d \n",strlen(mystring2),len10(mystring2));

  reverse_string(mystring1);
  printf("the value of palindrome is %d\n",palindrome("01210"));

  return 0;
}
```
### exc12.py
```python
def isPalindrome(string):
	left_pos = 0
	right_pos = len(string) - 1
	
	while right_pos >= left_pos:
		if not string[left_pos] == string[right_pos]:
			return False
		left_pos += 1
		right_pos -= 1
	return True
print(is Palindrome('aza')) 
```
