# Arrays - DS

```
Complete the function reverseArray in the editor below.

reverseArray has the following parameter(s):

int A[n]: the array to reverse
Returns

int[n]: the reversed array
```

```
Sample Input

4
1 4 3 2
```

```
Sample Output 

2 3 4 1
```

```
a =int(input())
b = list(map(int, input().split()))
def reverseArray(b):
    b.reverse()
    for i in b:
        print (i, end=" ")
reverseArray(b)
```
