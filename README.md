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
Developed by: singamala venkata sai kumar reddy
RegisterNumber:23004205 
'''
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large


```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by:singamala venkata sai kumar reddy 
RegisterNumber: 23004205
'''
def max_marks(marks):
    large=max(marks)
    return large


```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: singamala venkata sai kumar reddy
RegisterNumber: 23004205
'''
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max        


```
## Sample Input and Output
![sa 3a1](https://github.com/23004205/FindMaximum/assets/138971114/899d3cb8-2c59-4d5b-a21e-59bbfcf4978f)

![sa 3a 2](https://github.com/23004205/FindMaximum/assets/138971114/53ec37bc-2cc8-42bf-a1ce-2fc57e87000b)

![sa 3a 3](https://github.com/23004205/FindMaximum/assets/138971114/f5c194e3-f18c-4cb2-8e46-1b5e1aee5cef)

## Output:
![3a 1](https://github.com/23004205/FindMaximum/assets/138971114/4feb90bd-51b5-4ec8-bb4d-bc28358a2166)
![3a 2](https://github.com/23004205/FindMaximum/assets/138971114/bde79c59-5cfd-4e77-8264-f3402275b0df)
![3a 3](https://github.com/23004205/FindMaximum/assets/138971114/a49dc348-ab78-4f5f-afa4-c94918aa2272)

## Result:

Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
