# EX 1D Linear search
## DATE:
## AIM:
To write a python program for a search function with parameter list name and the value to be searched using string values.



## Algorithm
1.Loop through each element in the tuple.
2.Compare the current element with the target value x.
3.If the element matches x, print that the element was found and stop the search.
4.If no match is found after checking all elements, print that the element was not found.
5.End the function.  

## Program:
```
/*
Program to implement a search function with parameter list name and the value to be searched using string values.
Developed by: Srinidhi P
Register Number:212222040160  
*/
```
```
def search(tuple1,x):
    for value in tuple1:
        if(value==x):
            print("Tuple: %d found"%x)
            return 0
    print("Tuple: %d not found"%x)
    
List=[]
n=int(input())
for i in range(n):
    List.append(int(input()))
tuple1=tuple(List)
x=float(input())
search(tuple1,x)
```
## Output:
![image](https://github.com/user-attachments/assets/f2735623-b36d-407b-9695-5dcc5dab3454)



## Result:
The program was executed successfully, and it correctly checks if the input element is present in the list, printing "Found" if the element exists or "Not Found" if it does not.
