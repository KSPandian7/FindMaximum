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
Program to mark the maximum of marks using the list method sort
Developed by : kulasekarapandian
RegisterNumber : 22001410

l1=[]
def max_marks(marks):
    marks.sort()
    maximum = marks[-1]
    return maximum
```

## OUTPUT:
Using sort() method:
![output](/output1.png)

ii)	# To find the maximum marks using the list method max().
```Python
Program to find the maximum marks using the list method max().
Developed by : kulasekarapandian
RegisterNumber: 22001410

def max_marks(marks):
    marks= max(marks)
    return marks
```

## OUTPUT:
Using max() method:
![output](/output2.png)

iii) # To find the maximum marks without using builtin functions.
```Python
Program to the maximum marks without using builtin functions.
Developed by: kulasekarapandian
RegisterNumber: 22001410

def max_marks(list1):
    max1 = list1[0]
    for i in list1:
        if i > max1:
            max1 = i
    return max1
```
## OUTPUT:
Without using Built in function:
![output](/output3.png)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.