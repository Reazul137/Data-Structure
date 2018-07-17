<b>Data Structure:</b> In computer science, a data structure is a data organization and storage formate that enables efficient access and modification. More precisely, a data structure is a collection of data values, the relationship among them, and the sunctions or operations that can be applied to the data.<br>

<b>Classification of Data Structures :</b> Data Structures are generally classified into <b>1.primitive</b> and <b>2.Non-Primitive</b> data structures.<br>

<b>Primitive Data Structure :</b>Basic data types such as integer, real, character and boolean are known as primitive data structures. These data types consist of characters that can't be divided, and hence they are also called simple data types.<br>
There are four type of Primitive Data Structures, They are :
1. Integer
2. Real
3. Character
4. Boolean<br>

<b>Non-Primitive Data Structure: </b>  Non-Primitive data structure is the processing of complex numbers.very few computers are capable of doing arithmetic on comples numbers. Linked list, stacts, queues, trees and graphs are exapmples of non-primitive data structures.<br>
There are two types of Non-Primitive Data Structures, They are:
1. <b>Linear Data Structures : </b> A data structures is said to be linear if elements form a sequence or a linear list. In linear data structures, the data is arranged in a linear fashion although the way the are stored in memory need not be sequential.<br>
   Four types of Linear Data Structures :
     1. <b>Arrays :</b>An array is a data structure that contains a group of elements. Typically these elements are all of the same data type, such as an integer or string. Arrays are commonly used in computer programs to organize data so that a related set of values can be easily sorted or searched.
     2. <b>Linked List</b>
     3. <b>Stacks</b>
     4. <b>Queues</b>
2. <b>Non-Linear Data Structures :</b>A Data Structure is said to be non-linear if the data not arranged in sequence. The insertion and deletion of data is therefore not possible in a linear fashion.<br>
     There are two types of Non-Linear Data Structures, and they:
      1. <b>Trees</b>
      2. <b>Graphs</b><br>
     
 <b>Data Structures Operations : </b>The basic operations that are performed on data structures are as follows:<br>
      1. <b>Insertion : </b>Insertion means addition of a new data element in a data structure.<br>
      2. <b>Deletion  : </b>Deletion means removal of a data element from a data structure if it is found.<br>
      3. <b>Searching : </b>Searching involves searching for the specified data element in a data structure.<br>
      4. <b>Traversal : </b>Traversal of a data structure means processing all the data elements present in it.<br>
      5. <b>Sorting   : </b>Arranging data elements of a data structure in a specified order is called sorting.<br>
      6. <b>Merging   : </b>Combining elements of two similar data structures to form a new data structure of the same type, is called merging.<br>


<b>Shorting :</b> Sorting refers to ordering data in an increasing or decreasing fashion according to some linear relationship among the data items. Sorting can be done on names, numbers and records. Sorting reduces the For example, it is relatively easy to look up the phone number of a friend from a telephone dictionary because the names in the phone book have been sorted into alphabetical order.
 1. Sorting is the process of arrangining the data in some logical order.
 2. this logical order may be ascending or descending in case of numeric values or dictionary order in case of alphanumeric values.
    two types of shorting:<br>
     -- Internal shorting<br>
     -- External Sorting<br>
     
There are many types of shorting, they are : 
1. <b>Insertion Sort : </b> Insertion sort is a simple sorting algorithm that builds the final sorted array (or list) one item at a time. It is much less efficient on large lists than more advanced algorithms such as quicksort, heapsort, or merge sort.<br>
2. Merge Sort
3. Quick Sort
4. Radix Sort
5. Heap Sort
6. <B> Selection sort :</b> In computer science, selection sort is a sorting algorithm, specifically an in-place comparison sort. It has O(n²) time complexity, making it inefficient on large lists, and generally performs worse than the similar insertion sort.<br>
7. <b>Bubble Sort : </b> Bubble sort, sometimes referred to as sinking sort, is a simple sorting algorithm that repeatedly steps through the list to be sorted, compares each pair of adjacent items and swaps them if they are in the wrong order. The pass through the list is repeated until no swaps are needed, which indicates that the list is sorted.</br>

<b>Insertion Sort : </b>C program for insertion sort to sort numbers. This code implements insertion sort algorithm to arrange numbers of an array in ascending order. With a little modification, it will arrange numbers in descending order. Best case complexity of insertion sort is O(n), average and the worst case complexity is O(n2). <a href="https://www.geeksforgeeks.org/insertion-sort/">Insertion Sort.</a><br>

<b>Bubble Sort :</b>Bubble Sort is the simplest sorting algorithm that works by repeatedly swapping the adjacent elements if they are in wrong order. <a href="https://www.geeksforgeeks.org/bubble-sort/"> Bubble Sort</a><br>
1. Bubble Sort is very simple and easy to implement sorting technique.
2. Untill unless explicity stated sorting means ascending order.<br>
---** letes take an example,<br>
      we have a list of numbers stored in array :<br>
      A=[34,15,29,8]<br>
            0  1  2  3<br>
      logic starts with comparison of first two elements and if the left elements is greater than right element, they swap their position. Comparison proceeds till the end of array.
      


<b>Search :</b> a search algorithm is any algorithm which solves the search problem, namely, to retrieve information stored within some data structure, or calculated in the search space of a problem domain. Examples of such structures include but are not limited to a linked list, an array data structure, or a search tree. The appropriate search algorithm often depends on the data structure being searched, and may also include prior knowledge about the data. Searching also encompasses algorithms that query the data structure, such as the SQL SELECT command.
Searching Algorithm :
1. linear search
2. Binary Search
3. jump search
4. interpolation search
5. exponential searchsublist search(search a linked list in another list)
6. fibonacci search
7. the ubiquitous binary search
8. recursive program to linearly search an element in a given array
9. recursive function to do substring search
10. Unbounded Binary Search<br>

<b>Linear Search :</b> In computer science, linear search or sequential search is a method for finding a target value within a list. It sequentially checks each element of the list for the target value until a match is found or until all the elements have been searched.
<a href="https://www.geeksforgeeks.org/linear-search/" target="_blank">Linear search.</a><br>

<b>Binary Search:</b>In computer science, binary search, also known as half-interval search,logarithmic search, or binary chop, is a search algorithm that finds the position of a target value within a sorted array. Binary search compares the target value to the middle element of the array.
<a href="https://www.geeksforgeeks.org/binary-search/" target="_blank">Binary search.</a>

<b>Preliminaries : </b>


<h1>Chepter 3-- String Processing</h1>
  <b>Basic Terminology : </b>
    1. Alphabate
    2. Digits
    3. Special Character<br>
    
 <b>Shorting String : </b> Generally strings are sorted in three of structures : <br>
 1. Fixed-length Structures.
 2. Variable-length structures.
 3. Linked Structures. <br>
 
 <b>Character Data Type : </b> Each data type has its own formula for decoding a sequence of bits in memory : <br>
 1. Constants : Many programming language denote string sonstantsby placing the string in either single or double quotation marks, 
 for example, "THE END" or "TO BE OR NOT TO BE"
 2. Variables : Each programming language its own rules for forming character variables. However, such variables fall into one of three categories :
    1. Static.
    2. Semistatic.
    3. Dynamic.
  
<b>String Operations :</b>
1. Substring
2. Indexing
3. Concatanation
4. Length

  
