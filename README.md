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
''' 
Program to mark the maximum of marks using the list method sort

Developed by: NITHISHWAR S

RegisterNumber: 21002766

'''
def max_marks(marks):
            
    marks.sort()
    
    large=marks[-1]
    
    return large

ii)	# To find the maximum marks using the list method max().
''' 
Program to find the maximum marks using the list method max().

Developed by: NITHISHWAR S

RegisterNumber: 21002766

'''
def max_marks(marks):

    a=max(marks)
    
    return a

iii) # To find the maximum marks without using builtin functions.
''' 
Program to the maximum marks without using builtin functions.

Developed by: NITHISHWAR S

RegisterNumber: 21002766 

'''

def max_marks(list1):

    max_mark=0
    
    for i in list1:
    
        if i>max_mark:
        
            max_mark=i
            
    return max_mark


## Output:
(i) ![image](https://user-images.githubusercontent.com/94164665/149663564-e303d98a-7b95-4c43-ae79-bd3acfc1733f.png)
(ii)![image](https://user-images.githubusercontent.com/94164665/149663571-76992f65-d73e-4fe3-8331-3726d1d44076.png)
(iii)![image](https://user-images.githubusercontent.com/94164665/149663584-2d4acea0-a13b-47c7-b71a-2ae8f1c38891.png)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
