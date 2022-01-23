# Linear Search and Binary search
## Aim:
To write a program to perform linear search and binary search using python programming.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Linear Search:
1.	Start from the leftmost element of array[] and compare k with each element of array[] one by one.
2.	If k matches with an element in array[] , return the index.
3.	If k doesn’t match with any of elements in array[], return -1 or element not found.
## Binary Search:
1.	Set two pointers low and high at the lowest and the highest positions respectively.
2.	Find the middle element mid of the array ie. arr[(low + high)/2]
3.	If x == mid, then return mid.Else, compare the element to be searched with m.
4.	If x > mid, compare x with the middle element of the elements on the right side of mid. This is done by setting low to low = mid + 1.
5.	Else, compare x with the middle element of the elements on the left side of mid. This is done by setting high to high = mid - 1.
6.	Repeat steps 2 to 5 until low meets high
## Program:
i)	#Use a linear search method to match the item in a list.
```
def linearsearch(array, n, k):

    for i in range(0, n):
        if (array [i] == k):
            return i
    return -1

array = eval(input())
k =  eval(input())
n = len(array)
array.sort()
result = linearsearch(array, n, k)
if(result == -1):
    print(array)
    print("Element not found")
else:
    print(array)
    print("Element found at index: ", result)


```
ii)	# Find the element in a list using Binary Search(Iterative Method).
```
def linearsearch(array, n, k):

    for i in range(0, n):
        if (array [i] == k):
            return i
    return -1

array = eval(input())
k =  eval(input())
n = len(array)
array.sort()
result = linearsearch(array, n, k)
if(result == -1):
    print(array)
    print("Element not found")
else:
    print(array)
    print("Element found at index: ", result)





```
iii)	# Find the element in a list using Binary Search (recursive Method).
```
def linearsearch(array, n, k):

    for i in range(0, n):
        if (array [i] == k):
            return i
    return -1

array = eval(input())
k =  eval(input())
n = len(array)
array.sort()
result = linearsearch(array, n, k)
if(result == -1):
    print(array)
    print("Element not found")
else:
    print(array)
    print("Element found at index: ", result)




```
## Sample Input and Output
![Screenshot (22)](https://user-images.githubusercontent.com/94165415/150685364-b5eaebbd-37e2-4ec3-a5ef-b4a4d3f63f46.png)
![Screenshot (18)](https://user-images.githubusercontent.com/94165415/150685098-a76b6380-87bc-49f1-bf04-8ec1b5ffeff1.png)
 
## output
![Screenshot (19)](https://user-images.githubusercontent.com/94165415/150685320-33b8e3dc-94e9-4927-a59b-9b61faee87c5.png)
![Screenshot (20)](https://user-images.githubusercontent.com/94165415/150685351-0107c4fa-7ea3-47f3-8480-896c31772e98.png)
![Screenshot (21)](https://user-images.githubusercontent.com/94165415/150685350-82a0539f-df9a-423f-aabb-213c0f2f7734.png)

 





## Result
Thus the linear search and binary search algorithm is implemented using python programming.
