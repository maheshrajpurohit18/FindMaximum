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
Developed by: mahesh raj purohit
RegisterNumber:22008605 
'''
def max_marks(marks):
    marks.sort()
    large = marks[-1]
    return large



```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: mahesh raj purohit
RegisterNumber: 22008605
'''
def max_marks(marks):
   large = max(marks)
   return large



```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: mahesh raj purohit
RegisterNumber:22008605 
'''
def max_marks(list1):
    max = list1[0]
    for i in list1:
        if i > max:
            max = i
    return max



```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
To find the maximum of marks using the list method sort.
![Screenshot from 2023-01-23 22-15-06](https://user-images.githubusercontent.com/118749665/214101286-151d5e71-f7e4-41f3-851c-7de8a3adffab.png)
To find the maximum marks using the list method max().
![Screenshot from 2023-01-23 22-14-43](https://user-images.githubusercontent.com/118749665/214101456-047123cb-acaa-4096-a96d-5c53427e0986.png)
To find the maximum marks without using builtin functions.
![Screenshot from 2023-01-23 22-14-43](https://user-images.githubusercontent.com/118749665/214101552-7db7ad18-d249-4d04-993d-1f3508034171.png)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
