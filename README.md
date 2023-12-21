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
### Program:

i)	# To find the maximum of marks using the list method sort.
```Python
Program to mark the maximum of marks using the list method sort
Developed by: DHANUSYA K
RegisterNumber: 23006651
'''
def max_marks(marks):
    marks.sort()
    return marks[-1]



```

ii)	# To find the maximum marks using the list method max().
```Python
Program to find the maximum marks using the list method max().
Developed by: DHANUSYA K
RegisterNumber: 23006651
'''
def max_marks(marks):
    a=max(marks)
    return a


```

iii) # To find the maximum marks without using builtin functions.
```Python
Program to the maximum marks without using builtin functions.
Developed by: DHANUSYA K
RegisterNumber: 23006651
'''
def max_marks(list1):
    a=0
    for i in list1:
        if i>a:
            a=i
    return a


```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![Screenshot 2023-12-21 084033](https://github.com/Dhanu654/FindMaximum/assets/148514965/018299bb-5364-42a7-8657-4eaf42761f2c)
![Screenshot 2023-12-21 084421](https://github.com/Dhanu654/FindMaximum/assets/148514965/2f2e3983-5779-438c-bcab-5c01db3b76b2)
![Screenshot 2023-12-21 084504](https://github.com/Dhanu654/FindMaximum/assets/148514965/2e24bd4c-8fee-4d97-9f8f-63b68ec848b7)




## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
