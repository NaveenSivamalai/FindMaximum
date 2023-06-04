# Find the maximum of a list of numbers
## Aim:
To write a program to find the maximum of a list of numbers.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1.	Get the list of marks as input
2.	Use the sort() function or max() function or use the for loop to find the maximum mark.
3.	Return the maximum value
## Program:

i)	# To find the maximum of marks using the list method sort.
```Python
''' 
Program to mark the maximum of marks using the list method sort
Developed by: naveen s
RegisterNumber: 212222110030
'''
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
    #write your code here


```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: naveen s
RegisterNumber: 212222110030
'''
def max_marks(marks):
     marks.sort()
     return marks[-1]


```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: naveen s
RegisterNumber: 212222110030
'''
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i > max:
            max = i
    return max


```

## Output:
i)	# To find the maximum of marks using the list method sort.
![image](https://github.com/NaveenSivamalai/FindMaximum/assets/123792574/e5b97d72-303b-414f-89dc-1767e50ed691)

ii)	# To find the maximum marks using the list method max().
![image](https://github.com/NaveenSivamalai/FindMaximum/assets/123792574/8a8c9fb8-c5ff-424f-ae0a-084e27012bf7)

iii) # To find the maximum marks without using builtin functions.
![image](https://github.com/NaveenSivamalai/FindMaximum/assets/123792574/22bdcab8-b59d-4929-bf56-85da388c1615)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
