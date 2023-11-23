# Introduction to Arrays

## Table of Contents 

[[toc]]

## Java Arrays
Normally, an array is a collection of similar type of elements which has contiguous memory location.

Java array is an object which contains elements of a similar data type. Additionally, The elements of an array are stored in a contiguous memory location. It is a data structure where we store similar elements. We can store only a fixed set of elements in a Java array.

Array in Java is index-based, the first element of the array is stored at the 0th index, 2nd element is stored on 1st index and so on.


### Advantages
1) Code Optimization: It makes the code optimized, we can retrieve or sort the data efficiently.
2) Random access: We can get any data located at an index position.

### Disadvantages
1) Size Limit: We can store only the fixed size of elements in the array. It doesn't grow its size at runtime. To solve this problem, collection framework is used in Java which grows automatically.



## Example Of Java Array

```java
//Java Program to illustrate how to declare, instantiate, initialize  
//and traverse the Java array.  
class Testarray{  
public static void main(String args[]){  
int a[]=new int[5];//declaration and instantiation  
a[0]=10;//initialization  
a[1]=20;  
a[2]=70;  
a[3]=40;  
a[4]=50;  
//traversing array  
for(int i=0;i<a.length;i++)//length is the property of array  
System.out.println(a[i]);  
}}  
```
Output: 

```text
10
20
70
40
50
```

## Declaration, Instantiation and Initialization of Java Array

We can declare, instantiate and initialize the java array together by:

```java
int a[]={33,3,4,5};//declaration, instantiation and initialization  
```

Let's see the simple example to print this array.

```java
//Java Program to illustrate the use of declaration, instantiation   
//and initialization of Java array in a single line  
class Testarray1{  
public static void main(String args[]){  
int a[]={33,3,4,5};//declaration, instantiation and initialization  
//printing array  
for(int i=0;i<a.length;i++)//length is the property of array  
System.out.println(a[i]);  
}}    
```

Output:

```text
33
3
4
5
```

