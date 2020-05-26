# Binary Search
Introduction to binary search

### What Is Binary Search
Generally, binary search is an efficient way to search for a piece of information in a table.

##### What's the prerequisite of using binary research
The way a table stores the information should be sorted. Namely, the data should be stored either in an ascending order or a descending order.

##### How does a binary search work
Let's assume the elements in a table is arranged in an ascending order. Firstly, the procedure will compare the middle element in the table with the search key. If those two equal to each other, then the searching procedure is succeeded. If not, it will make a judgement. If the search key is greater than the middle element, it will go to the latter half of the table and compare the search key with the middle element of the latter half. If lower, it will go to the front half and do the same operation. The procedure will continue this loop until it finally find the element that equals to the search key.

##### Note
The two parts of the table do not have to be strictly the same length.
