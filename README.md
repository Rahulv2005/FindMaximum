# Find the maximum of a list of numbers
## Aim:
To write a program to find the maximum of a list of numbers.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
```
1.	Get the list of marks as input
2.	Use the sort() function or max() function or use the for loop to find the maximum mark.
3.	Return the maximum value
```
## Program:

i)	# To find the maximum of marks using the list method sort.
```Python
# Program to mark the maximum of marks using the list method sort.
# Developed by: RAGHUL V
# Register No:212223240132
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large






```

ii)	# To find the maximum marks using the list method max().
```Python
# Program to find the maximum marks using the list method max().
# Developed by: RAGHUL V
# Register No: 212223240132
def max_marks(marks):
    large=max(marks)
    return large





```

iii) # To find the maximum marks without using builtin functions.
```Python
# Program to find the maximum marks without using builtin functions.
# Developed by: RAGHUL V
# Register No: 212223240132
def max_marks(marks):
    max_mark=0
    for i in marks:
        if i>max_mark:
            max_mark=i
    return max_mark




```



## Output:
![image](https://github.com/Rahulv2005/FindMaximum/assets/152600335/e139ecc6-7cc3-4540-9c5d-2f80ef851bb8)
![image](https://github.com/Rahulv2005/FindMaximum/assets/152600335/2b8622c8-4d2a-4988-9437-f750695d1d00)
![image](https://github.com/Rahulv2005/FindMaximum/assets/152600335/e27a08e9-3dbb-4264-8bb4-3a58215363e3)
![image](https://github.com/Rahulv2005/FindMaximum/assets/152600335/e72d4a51-b11e-4de5-bcd8-cf9f268ba220)
![image](https://github.com/Rahulv2005/FindMaximum/assets/152600335/288e9372-916e-47ba-ab14-4e5a75b8fcfe)
![image](https://github.com/Rahulv2005/FindMaximum/assets/152600335/5d729578-f7f1-4190-9378-12a610a4c272)



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
