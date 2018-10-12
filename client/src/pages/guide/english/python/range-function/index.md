---
title: Range Method
---
# Range Function
If you do need to iterate over a sequence of numbers, the built-in function range() comes in handy. It generates arithmetic progressions:

#### Example Usage 1: 
**range(stop)** In the code below, the minimum required parameter is included, the *stop* index. 
**Note:** The range stops at the index before the *stop*. 
 ```py
for i in range(5):
    print(i)
 ```
 
 #### Output
 ```
0
1
2
3
4
 ```
 #### Example Usage 2: 
 **range(start, stop)** In the code below, the (optional) *start*ing index is included. 
 **Note:** Unlike with *stop*, the *start* is included in the range. 
 ```py
 for i in range(4,10):
     print(i)
 ```
 #### Output
```
4
5
6
7
8
9
```
