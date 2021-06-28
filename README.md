# Algorithms And Data Structures
This repository contains the implementations of different algorithms and data structures using java language

# Algorithms :

An algorithm is a number of steps to perform a perticular task.

# Data Structures :

Data structures are store and manipulate the data.

# Big O Notations :

Big O notations gives us a way to compare time complexity of an algorithm in a objective and hardware independent manner.

O(1)        Constant
O(logn)     Logarithmic
O(n)        Linear
O(nlogn)    n Log star n
O(n^2)      Quadratic

# Time complexity comparison :

O(1) < O(log n) < O(sqrt n) < O(n) < O(n log n) < O(n^2) < O(2^n) < O(n!)

# Arrays

Arrays are continous block of memory.

if we know the start address (X), the size of data element in array (Y) and index of element (i) to retrieve then it can be retrieved using X +(Y*i) 
Ex. Array of integer, each int is of size 4 bytes, lets say start address is 12 then we can retrive the elements as below :

12 + (4 * 0) = 12
12 + (4 * 1) = 16
12 + (4 * 1) = 16

In an object array the object address is stored at the index the actual object reside at some other location in memory.

Time complexity of array :

1. search by index : O(1)
2. search without index : O(n)
3. insert or update at index : O(1)
4. delete by index : O(1)
5. delete without index : O(n)

# Sorting :

# Stable and Unstable Sort Algorithms.

in case of stable sort algorithm, the relative order of the duplicate elements will be preserved.

in case of unstable sort algorithm, the relative order of duplicate elements will not be preserved.

stable sort is preffered not in case of integers but in case of objects or other data types.

# Bubble Sort

Bubble sort is an in place algorithm. 

It has a worst time complexity of O(n^2) (Quadratic)

It is a stable sort algorithm.

It creates a logical partition in the array and considers the nth index as unsorted array at the beginning as nothing is sorted. In each iteration it compared the consecutive array indexes from the beginning until unsorted index and move the large element to the end of unsorted array. In the next iteration unsorted array index reduces by one and sorted array length increases by one. the entire array gets sorted when unsorted index reached to 1.

# Selection Sort 

Selection sort is an in place algorithm.
 
It has a time complexity of O(n^2) (Quadratic)
 
It is an unstable algorithm.
 
In selection sort, the original array is logically divided into 2 sub arrays. an unsorted and a sorted array. An unsorted array index is defined as the last index of array which gets reduced in each iteration and hence in every iteration the unsorted array length decreases and sorted array length increase.

In every iteration, the 0th index is considered as the index holding the largest element in an array and it is compared with other elements from 1st index until the unsorted index, if the largest index holds lesser value than iterator index value then this index is marked as largest index, at the end of the iteration the largest index value is swiped with unsorted index value.
 
Unlike bubble sort this algorithm doesn't do a lot of swipes hence in certain cases it is considered better than bubble sort.
 



