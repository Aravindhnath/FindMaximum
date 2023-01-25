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
```
''' 
Program to mark the maximum of marks using the list method sort
Developed by: Aravindhnath T R 
RegisterNumber: 22009024
'''
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
```

ii)	# To find the maximum marks using the list method max().
```
''' 
Program to find the maximum marks using the list method max().
Developed by: Aravindhnath T R
RegisterNumber: 22009024
'''
def max_marks(marks):
    max=marks[0]
    for i in marks:
        if i>max:
            max=i
    return max
```

iii) # To find the maximum marks without using builtin functions.
```
''' 
Program to the maximum marks without using builtin functions.
Developed by: Aravindhnath T R
RegisterNumber: 22009024
'''
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max
```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
## Program 1:
![Screenshot_20230126_040025](https://user-images.githubusercontent.com/118790841/214707224-8222947e-4c29-4c38-91e8-4b97a0b1d071.png)
## Program 2:
![Screenshot_20230126_040046](https://user-images.githubusercontent.com/118790841/214707293-29ec9f44-4f45-4ea4-8235-8bad398db590.png)
## Program 3:
![Screenshot_20230126_040110](https://user-images.githubusercontent.com/118790841/214707316-691ad70e-3695-4832-ac16-55a459a9bc91.png)
## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
