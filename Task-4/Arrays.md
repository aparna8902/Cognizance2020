___
# **LIST OF CONCEPTS**
1. Arrays
1. Strings
1. Functions
1. Sorting
   * Bubble sort
   * Insertion sort
   * Selection sort
1. Pointers
___
## **ARRAYS**
___
### *What is an array?*
An array is a collection of items stored at contiguous memory locations and elements can be accessed randomly using indices of an array.

### *Why do we need arrays?*
We can use normal variables (v1, v2, v3, ..) when we have a small number of objects, but if we want to store a large number of instances, it becomes difficult to manage them with normal variables. The idea of an array is to represent many instances in one variable.

![Array declaration](https://media.geeksforgeeks.org/wp-content/cdn-uploads/Array-In-C.png)

*To learn more about arrays visit **[Arrays](https://www.geeksforgeeks.org/arrays-in-c-cpp/ "Geeks For Geeks article")***

___
### C++ Code for finding max using array
```c
#include <iostream>
using namespace std;

int n, a[n],max;
cout<<"Enter the number of elements";
cin>>n;
cout<<"Enter the elements";
for(int i=0;i<n;i++)
cin<<a[i];

max=a[0];
for(i=1;i<n;i++>)
if(a[i]>max)
max=a[i];

cout<<"Maximum of the array is: "<<max;
```
___
Here's a quote that can help you understand the colloquial usage of the term *array*
> Stupidity, outrage, vanity, cruelty, iniquity, bad faith, falsehood - we fail to see the whole ***array*** when it is facing in the same direction as we. ~ **Jean Rostand**
