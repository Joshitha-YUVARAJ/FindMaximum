## DATE:
## EX-6 Find the maximum of a list of numbers
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
def max_marks(array):
    array.sort()
    return array[-1]



```

ii)	# To find the maximum marks using the list method max().
```
def max_marks(array):
    return max(array)




```

iii) # To find the maximum marks without using builtin functions.
```
def max_marks(array):
    max1=array[0]
    for i in range(1,len(array)):
        if max1<array[i]:
            max1=array[i]
    return max1



```



## Output:
![Screenshot 2024-10-06 151741](https://github.com/user-attachments/assets/6828265d-5690-4689-84a4-c6df80c89dc1)
![Screenshot 2024-10-06 151917](https://github.com/user-attachments/assets/b1b2ae1b-5b7d-4346-83a6-6ee2fda614d8)
![Screenshot 2024-10-06 151947](https://github.com/user-attachments/assets/b4cd93ba-82da-4950-9be7-139365f56eda)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
