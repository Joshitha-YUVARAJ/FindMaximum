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
![image](https://github.com/user-attachments/assets/fa4a122c-0eca-48d4-b9cc-83b824f10f35)

![image](https://github.com/user-attachments/assets/3fe83fb0-649a-4785-ae39-7a32a20913b2)

![image](https://github.com/user-attachments/assets/6874b84d-3aa0-4db8-9904-73be2506fe53)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
