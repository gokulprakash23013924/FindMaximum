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
Developed by: GOKUL PRAKASH M
RegisterNumber: 23013924
'''
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large


```

ii)	# To find the maximum marks using the list method max().
```Python
Program to find the maximum marks using the list method max().
Developed by: GOKUL PRAKASH M
RegisterNumber: 23013924
'''
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max        


```

iii) # To find the maximum marks without using builtin functions.
```Python
Program to the maximum marks without using builtin functions.
Developed by: GOKUL PRAKASH M
RegisterNumber: 23013924
'''
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
    


```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![image](https://github.com/gokulprakash23013924/FindMaximum/assets/150231472/81e34602-534a-48cc-88ce-a274e8d2a097)
![image](https://github.com/gokulprakash23013924/FindMaximum/assets/150231472/ed1fd520-8c03-4f2c-b328-ab094a590458)
![image](https://github.com/gokulprakash23013924/FindMaximum/assets/150231472/37bc62a5-222c-4794-a736-c504a2f04c7e)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
