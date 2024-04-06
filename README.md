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
def max_marks(marks_list):

    marks_list.sort(reverse=True)

    return marks_list[0]




```

ii)	# To find the maximum marks using the list method max().
```Python

def max_marks(marks_list):

    return max(marks_list)




```

iii) # To find the maximum marks without using builtin functions.
```Python

def max_marks(marks_list):

    return max(marks_list)

```



## Output:
<img width="542" alt="Screenshot 2024-04-06 221722" src="https://github.com/SIVAmech123/FindMaximum/assets/151629067/a5264e19-5d04-49d3-bfc1-b310249dcf60">



<img width="598" alt="Screenshot 2024-04-06 221734" src="https://github.com/SIVAmech123/FindMaximum/assets/151629067/91f3e0fd-7499-410e-9eb7-7c56a7aec664">




<img width="398" alt="Screenshot 2024-04-06 221751" src="https://github.com/SIVAmech123/FindMaximum/assets/151629067/1dd22709-7fd0-42c0-b124-4e2ba51b700c">



<img width="523" alt="Screenshot 2024-04-06 221812" src="https://github.com/SIVAmech123/FindMaximum/assets/151629067/4f1115b3-b861-4cb8-80a4-7bcdcb61a9e0">





<img width="466" alt="Screenshot 2024-04-06 221845" src="https://github.com/SIVAmech123/FindMaximum/assets/151629067/79148d3b-d2f9-486b-a356-02e281fa89e3">




<img width="528" alt="Screenshot 2024-04-06 221903" src="https://github.com/SIVAmech123/FindMaximum/assets/151629067/62b14317-56a5-423d-ad55-01ee542defed">



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
