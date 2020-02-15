/******************************************************************************
 *  Name: Tristan Linn
 *
 *  Hours to complete assignment (optional):3-4
 *
 ******************************************************************************/

Programming Assignment 2: Autocomplete


/******************************************************************************
 *  Describe how your firstIndexOf() method in BinarySearchDeluxe.java
 *  finds the first index of a key that equals the search key.
 *****************************************************************************/
We find the first index key by using binary search. Once we find the mid which
is the value we are looking for, we check to the left of it and see if it is 
also the key. From there if it isn't the same to the left we return mid, if it is
we set the hi value to be mid-1 and continue binary searching until we find a place
where the left of mid doesn't equal the key.

/******************************************************************************
 *  What is the order of growth of the number of compares (in the
 *  worst case) that each of the operations in the Autocomplete
 *  data type make, as a function of the number of terms n and the
 *  number of matching terms m?
 *
 *  Recall that with order-of-growth notation, you should discard
 *  leading coefficients and lower-order terms, e.g., m^2 + m log n.
 *****************************************************************************/

constructor:N 

allMatches():N logN

numberOfMatches():LogN




/******************************************************************************
 *  Known bugs / limitations.
 *****************************************************************************/
None

/******************************************************************************
 *  Describe whatever help (if any) that you received.
 *  Don't include readings or lectures, but do include
 *  any help from people (including course staff, lab TAs,
 *  classmates, and friends) and attribute them by name.
 *
 *  Also include any resources (including the web) that you may
 *  may have used in creating your design.
 *****************************************************************************/
Kobe Sagami helped me figure out how to make the binary search time non-linear 
by checking the left/right of the midpoint depending if you're searching for the
high or low point and continuing the binary search.


/******************************************************************************
 *  Describe any serious problems you encountered.                    
 *****************************************************************************/
Comparing by Prefix Order gave me quite the fit. If your "r" or characters to look
at was longer than the string, it gave an error. I fixed this by using Math.min
and if r was bigger than the string length, we just used the strings length.



/******************************************************************************
 *  List any other comments here. Feel free to provide any feedback   
 *  on how much you learned from doing the assignment, and whether    
 *  you enjoyed doing it.                                             
 *****************************************************************************/
Learning about how to use comparators was a surprising result from this project.
This was a super rewarding assigment, it is so satifying to be able to quickly 
search so many cities around the world so effortlessly. 

  
